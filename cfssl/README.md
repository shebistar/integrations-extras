# Agent Check: cfssl

## Overview

This check monitors [cfssl][1] through the Datadog Agent.

## Setup

Follow the instructions below to install and configure this check for an Agent running on a host. For containerized environments, see the [Autodiscovery Integration Templates][3] for guidance on applying these instructions.

### Installation

The cfssl check is not included in the [Datadog Agent][2] package, so you need to install it.

### Configuration

1. Edit the `cfssl.d/conf.yaml` file, in the `conf.d/` folder at the root of your Agent's configuration directory to start collecting your cfssl performance data. See the [sample cfssl.d/conf.yaml][4] for all available configuration options.

2. [Restart the Agent][5].

### Validation

[Run the Agent's status subcommand][6] and look for `cfssl` under the Checks section.

## Data Collected

### Metrics

The cfssl integration does not include any metrics.

### Events

The cfssl integration does not include any events.

### Service Checks

See [service_checks.json][7] for a list of service checks provided by this integration.

## Troubleshooting

Need help? Contact [Datadog support][8].


[1]: https://github.com/cloudflare/cfssl
[2]: https://app.datadoghq.com/account/settings#agent
[3]: https://docs.datadoghq.com/agent/kubernetes/integrations/
[4]: https://github.com/DataDog/integrations-extras/blob/master/cfssl/datadog_checks/cfssl/data/conf.yaml.example
[5]: https://docs.datadoghq.com/agent/guide/agent-commands/#start-stop-and-restart-the-agent
[6]: https://docs.datadoghq.com/agent/guide/agent-commands/#agent-status-and-information
[7]: https://github.com/DataDog/integrations-extras/blob/master/cfssl/assets/service_checks.json
[8]: https://docs.datadoghq.com/help/
