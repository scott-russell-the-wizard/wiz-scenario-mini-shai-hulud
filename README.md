# Scenario: Mini Shai Hulud Supply Chain Attack

## Purpose
This scenario is designed to test Wiz's ability to detect packages compromised in the "Mini Shai Hulud" supply chain attack. This attack targeted SAP-related npm packages and other common libraries.

## Impacted Packages Included
- `@cap-js/sqlite`: v2.2.2 (npm)
- `@cap-js/postgres`: v2.2.2 (npm)
- `@cap-js/db-service`: v2.10.1 (npm)
- `intercom-client`: v7.0.5 (npm)
- `lightning`: v2.6.2 (PyPI)

## References
- [Wiz Blog: Mini Shai Hulud Supply Chain Attack](https://www.wiz.io/blog/mini-shai-hulud-supply-chain-sap-npm#indicators-of-compromise-39)

## Testing
Run a Wiz VCS scan on this repository to verify detection of these specific package versions.
