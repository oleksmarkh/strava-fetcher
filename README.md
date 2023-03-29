# strava-fetcher

  [![license][license-image]][license-url]
  ![code size][code-size-image]

Since the idea of turning the [activity-calendar-backend](https://github.com/oleksmarkh/activity-calendar-backend)
into a full-fledged backend is abandoned, and the [frontend](https://activity-calendar.netlify.app/) remains static,
this tool will do the ETL job.

## Status
*draft*

## What makes it possible?
{list: deps, dev deps, data sets, etc.}

## Development setup
{env vars, installing deps, testing}
```bash
# install deps and build the binary
$ cargo build

# lint the codebase, requires Clippy component to be installed
$ cargo clippy

# run unit tests
$ cargo test

# copy the template file and fill missing values
$ cp .env.example .env

# run the binary
$ cargo run
```

## Resources
- Registering a [Strava app](https://www.strava.com/settings/api).
- Strava [`/athlete/activities` API endpoint](https://developers.strava.com/playground/#/Activities/getLoggedInAthleteActivities).

[license-image]: https://img.shields.io/github/license/oleksmarkh/strava-fetcher.svg?style=flat-square
[license-url]: https://github.com/oleksmarkh/strava-fetcher/blob/master/LICENSE
[code-size-image]: https://img.shields.io/github/languages/code-size/oleksmarkh/strava-fetcher.svg?style=flat-square
