# Bug Bounty

## Overview

The security of Dopex users is paramount. For that reason, starting on May 17th 2023, the Dopex Protocol core repository is subject to the Dopex Bug Bounty (the “Program”). The Program enables community members to submit reports of “bugs” or vulnerabilities for a chance to earn rewards. The Program aims to incentivize responsible disclosure and enhance the security of Dopex.

Rewards will be allocated based on the severity of the bug disclosed and evaluated and rewarded up to **$250,000**.

The scope, terms and rewards at the sole discretion of the dopex team (the “Team”).

## Scope

The Program includes the vulnerabilities and bugs in the smart contracts deployed which compose the Dopex Platform.

Current contract scope:

**SsovV3:**

- https://docs.dopex.io/developer/contracts/arbitrum#ssov-v3
- https://docs.dopex.io/developer/contracts/polygon#ssov-v3

**OLP:**

- https://docs.dopex.io/developer/contracts/arbitrum#option-liquidity-pools-olps

**Atlantic Straddles:**

- https://docs.dopex.io/developer/contracts/arbitrum#atlantic-straddles
- https://docs.dopex.io/developer/contracts/polygon#atlantic-straddles

**Option Scalps:**

- https://docs.dopex.io/developer/contracts/arbitrum#option-scalps

**ZDTE Options:**

- https://docs.dopex.io/developer/contracts/arbitrum#zdte-options

The following are not within the scope of the Program:

- Bugs in any third party contract or platform that interacts with Dopex
- Bugs found in legacy/deprecated contracts
- Vulnerabilities related to domains, DNS, servers of websites, or website application related code
- Vulnerabilities already reported and/or discovered in contracts built by third parties on Dopex
- Any already-reported bugs or other vulnerabilities

Determinations of eligibility, score and all terms related to rewards and their payment are at the sole discretion of the Team.

# Eligibility

To be eligible for a reward under this Program, you must:

- Discover a previously unreported, non-public vulnerability within the scope of this Program. Vulnerabilities must be distinct from the issues covered in the previously conducted publicly available audits.
- Be the first to disclose the unique vulnerability to the Team by the disclosure requirements below. If similar vulnerabilities are reported, the first submission shall be rewarded (if determined valid and otherwise in the scope of this Program).
- Possess sufficient technical knowledge and provide sufficient information necessary to reproduce and fix the vulnerability.
- Not engage in any unlawful conduct when disclosing the bug, including through threats, demands, or any other coercive tactics.
- Not exploit the vulnerability in any way, including by making it public or obtaining a profit (other than a reward under this Program). Any publicity in any way, whether direct or indirect, relating to any bug or vulnerability will automatically disqualify it and you from the Program.
- Submit only one vulnerability per submission unless you need to chain vulnerabilities to impact any vulnerabilities. If you want to add more information to a provided issue, create a new submission referencing the initial one.
- Not submit a separate vulnerability caused by an underlying issue that is the same as an issue on which a reward has been paid under this Program.

## Disclosure

Any vulnerability or bug discovered must be reported to the Team via [security@dopex.io](mailto:security@dopex.io). The disclosure must be made within 24 hours following the discovery of the vulnerability and, as noted above, not have been exploited in any way prior to disclosure or publicized or disclosed to any third party (other than the Team) prior to not only submission of the report, but also fixing of the bug / vulnerability.

## Rewards

All submissions are evaluated by the Team on a case by case basis. Rewards are allocated based on the severity of the issue, and other variables, including, but not limited to a) the quality of the issue description, b) the instructions for reproducibility, and c) the quality of the fix (if included). A detailed report of a vulnerability increases the likelihood of a reward and may increase the reward amount. Therefore, please provide as much information about the vulnerability as possible.

The Program intends to follow a similar approach as the Ethereum Bug Bounty, where the severity of the issues will be based according to the OWASP risk rating model based on “Impact” and “Likelihood”. The evaluation on scoring is however at the sole discretion of the Team.

All rewards will be paid in tokens (comprising of at least 50% stablecoins) via a transfer to the wallet address provided by the participant to the Team.

Note that the reward cannot exceed over 30% of the total exploitable value of the bug.

The current bug bounty structure is:

|                    | Moderate | High    | Critical     |
| ------------------ | -------- | ------- | ------------ |
| **Almost Certain** | $10,000  | $50,000 | **$250,000** |
| **Likely**         | $5,000   | $10,000 | $50,000      |
| **Possible**       | $1,000   | $5,000  | $10,000      |

## Other terms

The decisions made regarding rewards are final and binding.

All reward decisions, including eligibility for and amounts of the rewards and how such rewards will be paid, are made at sole discretion of the Team.

Terms and conditions of the Program may be altered at any time.
