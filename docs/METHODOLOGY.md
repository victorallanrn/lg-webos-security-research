# Research Methodology

## 1. Define the question

State the target behavior and why it matters. Distinguish a hypothesis from a finding.

## 2. Record the environment

Log the device model, region, webOS version, firmware version, developer mode status, network isolation, and test date. Do not publish serial numbers, MAC addresses, or credentials.

## 3. Establish a baseline

Document the expected behavior using vendor documentation or a reproducible control test.

## 4. Perform authorized, non-destructive testing

Prefer read-only diagnostics and reversible changes. Record exact inputs, expected results, actual results, and any limitations. Avoid testing third-party systems.

## 5. Validate

Repeat the observation, compare across versions where available, and rule out alternate explanations. Do not infer a security vulnerability from unexpected behavior alone.

## 6. Classify evidence

- **Observed:** directly witnessed but not independently reproduced.
- **Reproduced:** repeated with documented steps.
- **Hypothesis:** unverified explanation.
- **Third-party report:** sourced externally and not independently validated.

## 7. Disclose responsibly

Privately report actionable security issues to the appropriate vendor before publishing sensitive details.
