# Introduction

Healthchecks is a cron job monitoring service. It listens for HTTP requests and email messages ("pings") from your cron jobs and scheduled tasks ("checks"). When a ping does not arrive on time, Healthchecks sends out alerts.

TrueCharts are designed to be installed as TrueNAS SCALE app only. We can not guarantee this charts works as a stand-alone helm installation.
**This chart is not maintained by the upstream project and any issues with the chart should be raised [here](https://github.com/truecharts/apps/issues/new/choose)**

## Source Code

* <https://github.com/healthchecks/healthchecks>
* <https://hub.docker.com/r/linuxserver/healthchecks>

## Requirements

Kubernetes: `>=1.16.0-0`

## Dependencies

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org | common | 8.0.13 |

## Installing the Chart

To install this App on TrueNAS SCALE check our [Quick-Start Guide](https://truecharts.org/manual/Quick-Start%20Guides/03-Installing-an-App/).

## Uninstalling the Chart

To remove this App from TrueNAS SCALE check our [Quick-Start Guide](https://truecharts.org/manual/Quick-Start%20Guides/07-Deleting-an-App/).

## Support

- Please check our [quick-start guides](https://truecharts.org/manual/Quick-Start%20Guides/01-Open-Apps/) first.
- See the [Wiki](https://truecharts.org)
- Check our [Discord](https://discord.gg/tVsPTHWTtr)
- Open a [issue](https://github.com/truecharts/apps/issues/new/choose)
---
All Rights Reserved - The TrueCharts Project