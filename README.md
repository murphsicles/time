# @time/time — Date and Time Library for Zeta

Auto-converted from [time](https://crates.io/crates/time) v0.3.47 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **OffsetDateTime** — date/time with UTC offset, nanosecond precision
- **PrimitiveDateTime** — date/time without timezone
- **Date** — year, month, day with comprehensive arithmetic
- **Time** — hour, minute, second, nanosecond
- **Duration** — signed duration with nanosecond precision
- **Formatting/parsing** — strftime-style format strings, ISO 8601, RFC 2822, RFC 3339
- **Serde** — serialization support via `@data/serde`

## Usage
```zeta
use @time/time::OffsetDateTime;

let now = OffsetDateTime::now_utc();
println!("{}", now.format("%Y-%m-%d %H:%M:%S"));
```

## Stats: ~9,553 lines, 0 unsupported items

## License: MIT