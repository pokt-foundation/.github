# .allstar
Allstar configuration for pokt-foundation repos

[Allstar](https://github.com/ossf/allstar) is a security-policy GitHubApp. It is
installed on this org, and this repo contains the configuration for that app. It
is configured to create issues on repos that do not comply with the configured
policy.

## Policy Configuration
These are the expected settings to be in compliance

### [Branch Protection](branch_protection.yaml)

| | |
| - | - |
| Branches enforced | default |
| Require approval | yes |
| Approvals required | 1 |
| Dismiss stale reviews | not required |
| Block force push | yes |


### Policies Needed

The following policies are still needed:

### [Binary Artifacts](binary_artifacts.yaml)

- list policies around binary artifacts.

### [Outside Collaborators](outside.yaml)

- list out side collaborators policies

### [SECURITY.md](security.yaml)

- SECURITY.md required.