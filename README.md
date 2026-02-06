# Homebrew Tap for GrooveKit CLI

Official Homebrew tap for the [GrooveKit](https://groovekit.io) command-line interface.

## What is GrooveKit?

GrooveKit is a monitoring service for cron jobs and APIs. The CLI provides a powerful command-line interface to manage your monitors, view check history, and track incidents.

## Installation

```bash
brew install scookdev/groovekit/groovekit
```

## Usage

```bash
# Authenticate
groovekit auth login

# Manage cron job monitors
groovekit jobs list
groovekit jobs create --name "Daily Backup" --interval 1440

# Manage API monitors
groovekit monitors list
groovekit monitors create --name "Production API" --url https://api.example.com/health --interval 60

# View account info
groovekit account show

# Get help
groovekit --help
```

## Features

- **Cron Job Monitoring**: Heartbeat ping monitoring with configurable intervals and grace periods
- **API Monitoring**: HTTP endpoint health checks with response time tracking
- **Incident Tracking**: View downtime history and incident details
- **Check History**: Review recent pings and health check results
- **Account Management**: View subscription details and usage limits

## Documentation

For more information, visit [groovekit.io](https://groovekit.io).

## Support

Need help? Contact us at [groovekit.io/contact](https://groovekit.io/contact).

## License

MIT
