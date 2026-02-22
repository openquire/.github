
# 💰 openQuire Contributor Revenue Sharing Policy

> **Document Status**: Draft v1.0  
> **Last Updated**: [Insert Date]  
> **Applicable To**: All contributors to openQuire open-source repositories  
> **Governed By**: openQuire Organization  
> **Contact**: `payouts@openquire.org`

---

## 🎯 1. Purpose & Vision

openQuire believes that **those who build the software should share in its success**.

This Revenue Sharing Policy establishes a transparent, merit-based system where top open-source contributors earn a portion of revenue generated from the **openQuire Enterprise** hosted service.

**Our Goals:**
- ✅ **Reward** meaningful contributions to the open-source project.
- ✅ **Align** community incentives with long-term project sustainability.
- ✅ **Maintain** full transparency in calculations and payouts.
- ✅ **Foster** a collaborative, stakeholder-minded community.

---

## 📊 2. The Revenue Model

### 2.1 Revenue Flow
Enterprise subscription revenue is allocated as follows:

```
Enterprise Monthly Revenue
         │
         ▼
┌─────────────────────┐
│ Revenue Allocation  │
├─────────────────────┤
│ 40% → Infrastructure│ (Hosting, Support, Ops)
│ 30% → Business Fund │ (Reserves, Legal, Marketing)
│ 30% → Contributor   │ (The Pool)
│        Pool         │
└─────────────────────┘
         │
         ▼
┌─────────────────────┐
│ Contributor Pool    │
│ Distributed to Top  │
│ 10 Contributors     │
│ (by quarterly score)│
└─────────────────────┘
```

### 2.2 Pool Calculation
| Component | Formula |
|-----------|---------|
| **Gross Enterprise Revenue** | Sum of all paid subscriptions (net of refunds/chargebacks) |
| **Net Revenue** | Gross Revenue − Payment Processing Fees (≈2.9% + $0.30) |
| **Contributor Pool** | Net Revenue × **30%** |
| **Distribution Period** | Quarterly (Jan-Mar, Apr-Jun, Jul-Sep, Oct-Dec) |

> 🔄 *The 30% pool allocation may be adjusted annually via community proposal + maintainer approval.*

---

## 🏆 3. Eligibility

### 3.1 Basic Requirements
To be eligible for revenue share in a given quarter, a contributor must:

1. **Have at least 1 merged contribution** to an openQuire OSS repository during the quarter.
2. **Have signed the Contributor License Agreement (CLA)**.
3. **Have a verified GitHub account** linked to a valid payout method (PayPal, Stripe, etc.).
4. **Be in good standing** per the [Code of Conduct](https://github.com/openQuire/.github/blob/main/CODE_OF_CONDUCT.md).

### 3.2 Exclusions
The following do **not** count toward revenue share eligibility:
- ❌ Spam, low-effort, or automated PRs.
- ❌ Contributions to forks not merged upstream.
- ❌ Non-code contributions without prior maintainer approval.
- ❌ Contributors who violate the Code of Conduct during the quarter.

---

## 📈 4. Contribution Scoring System

Contributors are ranked by a **quarterly contribution score**. Higher score = larger share of the pool.

### 4.1 Score Formula
```
Total Score = 
  (Code PRs Merged × 15) +
  (Bug Fixes Merged × 20) +
  (Feature PRs Merged × 25) +
  (Documentation PRs × 10) +
  (Code Reviews Completed × 5) +
  (Issues Triage/Labels × 3) +
  (Community Support × 2) +
  (Maintainer Bonus × 0-50)
```

### 4.2 Weight Rationale
| Contribution Type | Weight | Why |
|------------------|--------|-----|
| **Feature PRs** | 25 | Drives product value |
| **Bug Fixes** | 20 | High impact on stability |
| **Code PRs (general)** | 15 | Core development work |
| **Documentation** | 10 | Critical for adoption |
| **Code Reviews** | 5 | Improves code quality |
| **Issue Triage** | 3 | Reduces maintainer load |
| **Community Help** | 2 | Fosters healthy ecosystem |
| **Maintainer Bonus** | 0-50 | Discretionary for exceptional leadership |

### 4.3 Example Calculation
```
Contributor: @alice
- 3 bug fixes: 3 × 20 = 60
- 1 feature PR: 1 × 25 = 25
- 5 code reviews: 5 × 5 = 25
- 10 community replies: 10 × 2 = 20
→ Total Score: 130

If top 10 scores sum to 1,000 and pool = $3,000:
Alice's Share = (130 / 1000) × $3,000 = $390
```

> 📝 *Weights and formula reviewed quarterly. Changes require 2-week notice + community discussion.*

---

## 💸 5. Payout Process

### 5.1 Timeline (Quarterly Cycle)
```
Quarter Ends (e.g., Mar 31) 
   │
   ▼
Week 1: Score calculation + draft report published
Week 2: Community review period (appeals window)
Week 3: Final scores locked + payout amounts calculated
Week 4: Payouts initiated via Stripe Connect / PayPal
```

### 5.2 Payout Methods
| Method | Minimum Payout | Regions Supported |
|--------|---------------|-------------------|
| **Stripe Connect** | $10 | Global (with tax form) |
| **PayPal** | $25 | Most countries |
| **Bank Transfer** | $100 | US, EU, UK only |
| **Crypto (USDC)** | $50 | Global (optional) |

> ⚠️ Payouts under the minimum threshold roll over to the next quarter.

### 5.3 Tax & Legal Compliance
- Contributors are responsible for reporting income per local laws.
- openQuire will issue tax forms where legally required (e.g., US 1099-NEC for >$600/year).
- Non-US contributors may need to submit W-8BEN form.
- Payouts are processed as "independent contractor" payments.

---

## 🔍 6. Transparency & Reporting

### 6.1 Public Dashboard
A live dashboard at **`openquire.org/transparency`** will display:

- ✅ **Current Quarter**: Enterprise MRR, Contributor Pool size, Top 20 Contributors (scores).
- ✅ **Historical Payouts**: Quarterly breakdowns (CSV download available).
- ✅ **Methodology**: Scoring formula version, adjustments, appeals resolved.

### 6.2 Quarterly Report Template
Each quarter, we publish a report similar to this:

```markdown
## openQuire Revenue Share Report — Q1 2026

### Financial Summary
- Gross Enterprise Revenue: $12,450
- Processing Fees: -$387
- Net Revenue: $12,063
- Contributor Pool (30%): $3,619

### Distribution
| Rank | Contributor | Score | Share | Status |
|------|-------------|-------|-------|--------|
| 1 | @alice | 210 | $762 | ✅ Paid |
| 2 | @bob | 185 | $671 | ✅ Paid |
| ... | ... | ... | ... | ... |
| 10 | @julia | 45 | $163 | ✅ Paid |
```

---

## ⚖️ 7. Governance & Modifications

### 7.1 Policy Changes
- **Minor Adjustments** (e.g., score weights): Proposed by maintainers, 7-day community comment period.
- **Major Changes** (e.g., pool %, eligibility): Requires community proposal + 2-week discussion + maintainer vote.

### 7.2 Community Input
- All proposals discussed in **GitHub Discussions** under `revenue-share` category.
- Core contributors (5+ merged PRs) receive voting weight on major changes.

### 7.3 Program Termination
openQuire reserves the right to modify or end this program with:
- 90 days written notice.
- Full payout of any accrued but unpaid shares.
- Community consultation prior to final decision.

---

## ❓ 8. Frequently Asked Questions

**Q: Do I need to be a full-time contributor to qualify?**  
**A**: No. Any merged contribution counts. Quality > quantity.

**Q: What if I contribute to multiple repos?**  
**A**: Scores aggregate across all openQuire OSS repositories (`core`, `docs`, `sync-server`, etc.).

**Q: Can companies/teams participate?**  
**A**: Yes, but payouts go to a single designated individual or legal entity. Teams must self-allocate.

**Q: What if enterprise revenue is $0 in a quarter?**  
**A**: The pool is $0. No payouts that quarter. Scores still accumulate for ranking.

**Q: Is this legally binding?**  
**A**: This policy reflects our commitment, but payouts are discretionary until formally agreed per quarter. We strive for consistency and transparency.

**Q: How are disputes handled?**  
**A**: 
1. Submit appeal via GitHub Issue (label: `revenue-appeal`) within 7 days of draft report.
2. Maintainer review + community input.
3. Final decision published with rationale.

---

## 📬 9. Contact & Support

| Purpose | Contact |
|---------|---------|
| General Questions | `community@openquire.org` |
| Payout Issues | `payouts@openquire.org` |
| Policy Appeals | Open GitHub Issue with `revenue-appeal` label |
| Legal Inquiries | `legal@openquire.org` |

---

## 📜 10. Appendix: Example Payout Calculation

```
Scenario: Q2 2026
- Enterprise Subscriptions: 150 users @ $8/mo = $1,200/mo → $3,600/quarter
- Payment Fees (3%): -$108
- Net Revenue: $3,492
- Contributor Pool (30%): $1,047.60

Top 10 Scores: [210, 185, 160, 130, 110, 95, 80, 70, 60, 50] = 1,150 total

Payout for Rank 1 (@alice):
  (210 / 1150) × $1,047.60 = $191.40

Payout for Rank 10 (@julia):
  (50 / 1150) × $1,047.60 = $45.55
```

---

## ⚠️ 11. Legal Disclaimer

> **This document is for informational purposes only and does not constitute legal or financial advice.**  
> openQuire recommends contributors consult a tax professional regarding income reporting.  
> openQuire reserves the right to modify this policy in accordance with Section 7.

---

## ✍️ 12. Acknowledgements

This policy draws inspiration from:
- [Sourcegraph's Contributor Program](https://about.sourcegraph.com/handbook/engineering/distribution/contributor_program)
- [GitCoin's Open Source Funding Models](https://gitcoin.co)
- [Buffer's Open Salary & Transparency Practices](https://buffer.com/transparency)

---

© 2026 openQuire Organization. Built with ❤️ by the community.
```