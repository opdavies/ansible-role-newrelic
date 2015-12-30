# Ansible Role: New Relic

Installs the New Relic agent for PHP.

## Requirements

Requires PHP to be installed.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

    newrelic_daemon: newrelic-daemon

The name of the New Relic daemon.

    newrelic_license_key: ''

Your license key.

    newrelic_app_name: 'PHP Application'

The default application name.

    newrelic_extra_parameters: ''

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
         - { role: opdavies.newrelic, newrelic_license_key: "123456789" }

## License

MIT

## Author Information

[Oliver Davies](https://www.oliverdavies.uk) - Drupal/PHP Developer and Linux System Administrator.
