# Xero v Volker Highways Ltd — account, CIS and VAT review

Source: Xero, North Herts Utilities Limited (company 08418914, GBP, financial
year 1 March to 28 February). Data pulled 12 September 2026.

Volker Highways appears in Xero as **both a customer and a supplier**.

## 1. What Xero shows today

| Item | Xero figure |
|------|------------:|
| Cash at bank | 34.94 |
| Trade debtors (aged receivables, none Volker) | 1,146.00 |
| Trade creditors, all overdue | 102,399.01 |
| of which owed to Volker (5 bills, Aug 2025) | 57,473.70 |
| "Other current assets" on the balance sheet | 1,010,837.46 |
| "Amount owed to you" per Xero cash position | 1,387,778.36 |

The last two lines are the important ones. Trade debtors are only 1,146, yet
Xero reports about 1.0m to 1.4m of current assets that are neither cash nor
trade debtors. The Xero connection used here only returns the balance sheet at
summary level, so the individual account cannot be read, but the movement
matches the CIS deductions (section 3). The two figures also disagree with
each other, which needs checking in Xero itself.

## 2. Sales to Volker — 270 invoices, all marked paid

| Year | Invoices | Invoiced (gross) | Received | CIS deducted |
|------|---------:|-----------------:|---------:|-------------:|
| 2020 | 30 | 1,215,969.95 | 1,013,308.28 | 202,661.67 |
| 2021 | 55 | 1,501,787.08 | 1,210,926.05 | 290,861.03 |
| 2022 | 52 | 1,687,629.69 | 1,350,103.76 | 337,525.93 |
| 2023 | 52 | 2,016,706.46 | 1,613,365.16 | 403,341.30 |
| 2024 | 52 | 2,058,861.54 | 1,648,604.40 | 410,257.14 |
| 2025 | 29 | 1,229,593.01 | 997,508.88 | 232,084.13 |
| **Total** | **270** | **9,710,547.73** | **7,833,816.53** | **1,876,731.20** |

- On every invoice bar one, the amount received is the invoice total less
  20% of the net. That is a standard-rate CIS deduction on labour, applied by
  Volker at payment. The one exception is INV-0231 (24,000, August 2025),
  paid in full with no deduction and coded to Sales - General.
- First invoice 2 March 2020, last 1 August 2025. No Volker sales since.
- The Xero profit and loss reconciles to these invoices exactly:
  - FY to Feb 2025: CIS Labour Income 2,038,692.95 = Volker net invoices.
  - FY to Feb 2026: CIS Labour Income 928,214.22 = Volker net invoices
    excluding INV-0231.
  - So Volker is effectively the company's only CIS customer.

## 3. CIS deducted by Volker and not visibly claimed

CIS deducted by Volker, by HMRC tax year (6 April to 5 April), using the
date each invoice was paid:

| Tax year | Invoices paid | Received | CIS deducted |
|----------|-------------:|---------:|-------------:|
| 2019/20 | 4 | 98,719.16 | 19,743.83 |
| 2020/21 | 40 | 1,231,579.62 | 250,295.01 |
| 2021/22 | 53 | 1,195,164.53 | 298,791.10 |
| 2022/23 | 52 | 1,356,667.99 | 339,167.00 |
| 2023/24 | 52 | 1,646,030.53 | 411,507.64 |
| 2024/25 | 51 | 1,673,366.78 | 414,909.04 |
| 2025/26 (to Aug 2025) | 18 | 632,287.92 | 142,317.58 |
| **Total** | **270** | **7,833,816.53** | **1,876,731.20** |

Same figures by the company's own financial year (March to February):

| Financial year | CIS deducted |
|----------------|-------------:|
| FY to Feb 2021 | 240,452.59 |
| FY to Feb 2022 | 297,497.57 |
| FY to Feb 2023 | 355,933.45 |
| FY to Feb 2024 | 382,466.16 |
| FY to Feb 2025 | 398,530.28 |
| FY to Feb 2026 | 201,851.15 |

Monthly, since 1 March 2025: Mar 48,818.72; Apr 26,590.03; May 21,265.68;
Jun 33,838.00; Jul 28,877.08; Aug 42,461.64.

**Why it looks unclaimed.** Balance sheet "other current assets" moved as
follows:

| Date | Other current assets | Change |
|------|---------------------:|-------:|
| 29 Feb 2024 | 351,299.08 | |
| 28 Feb 2025 | 738,988.50 | +387,689.42 |
| 31 Aug 2025 | 976,521.16 | +237,532.66 |
| 12 Sep 2026 | 1,010,837.46 | +34,316.30 |

CIS deducted over the same periods was 398,530 (FY to Feb 2025) and 201,851
(Mar to Aug 2025). The asset balance is growing at almost exactly the rate
CIS is being deducted, and it has not come down since. That is what you would
expect if CIS suffered is being posted to the CIS asset account on each
receipt but never cleared, either by monthly EPS set-off against PAYE/NIC or
by a year-end repayment claim to HMRC.

What to check in Xero directly (not visible through this connection):
1. The balance on the CIS deductions / CIS suffered asset account.
2. Whether any journals reduce it for PAYE set-off or HMRC repayments.
3. The CIS suffered figures reported on the monthly EPS submissions.

If the balance is around 1.0m, that is several tax years of unrecovered CIS.
The two most recent full years alone are 411,507.64 (2023/24) and
414,909.04 (2024/25). Older years may be caught by HMRC time limits, so the
accountant should prioritise those.

## 4. VAT points

- **Reverse charge.** From 1 March 2021 the construction reverse charge
  applies and 253 of the invoices correctly carry no VAT. Eight invoices
  between November 2024 and June 2025 did charge 20% VAT, and Volker paid it:

  | Invoice | Date | VAT charged |
  |---------|------|------------:|
  | INV-0173 | 15 Nov 2024 | 7,575.77 |
  | INV-0207 | 19 Mar 2025 | 6,154.79 |
  | INV-0211 | 11 Apr 2025 | 8,022.75 |
  | INV-0212 | 07 Apr 2025 | 7,852.42 |
  | INV-0213 | 25 Apr 2025 | 4,967.69 |
  | INV-0219 | 16 May 2025 | 7,305.67 |
  | INV-0226 | 20 Jun 2025 | 5,662.87 |
  | INV-0227 | 27 Jun 2025 | 5,206.20 |
  | **Total** | | **52,748.16** |

  Either these were genuinely outside the reverse charge, or they were
  standard-rated in error. Either way the output VAT must have been declared
  to HMRC, and Volker may query it. Worth confirming with the accountant.

- **Input VAT on Volker bills.** The 71 Volker bills (Sep 2024 to Aug 2025)
  total 736,136.52 including 122,689.42 of VAT. Confirm that VAT has been
  reclaimed on the returns covering those periods, including the five unpaid
  bills (9,578.95 VAT) if the company is on accruals VAT.

## 5. Purchases from Volker — 71 bills

| Year | Bills | Total incl. VAT |
|------|------:|----------------:|
| 2024 (from 26 Sep) | 17 | 210,562.61 |
| 2025 (to 14 Aug) | 54 | 525,573.91 |
| **Total** | **71** | **736,136.52** |

These are coded to "Materials (Volker)" in cost of sales (253,472.21 in FY to
Feb 2025, 359,974.88 in FY to Feb 2026). From January 2025 Volker bills in
weekly pairs: a variable amount plus a fixed 2,400 (2,000 plus VAT).

Unpaid, all overdue by more than a year:

| Bill | Date | Due | Amount |
|------|------|-----|-------:|
| SIN0008071 | 07 Aug 2025 | 14 Aug 2025 | 14,077.94 |
| SIN0008072 | 07 Aug 2025 | 14 Aug 2025 | 4,800.00 |
| SIN0008076 | 07 Aug 2025 | 14 Aug 2025 | 19,395.76 |
| SIN0008170 | 14 Aug 2025 | 21 Aug 2025 | 2,400.00 |
| SIN0008193 | 14 Aug 2025 | 21 Aug 2025 | 16,800.00 |
| **Total** | | | **57,473.70** |

They were raised in the same weeks as the last batch of sales receipts
(14 Aug 2025). Check whether Volker netted them off against those receipts
and they simply need marking as paid by contra.

## 6. Other numbers that look wrong in Xero

Profit and loss, FY to Feb 2026, has several expense accounts with credit
(negative) balances, which usually means miscoded bank transactions or
reversals:

| Account | FY to Feb 2026 | FY to Feb 2025 |
|---------|---------------:|---------------:|
| Direct Wages | -130,018.60 | 42,373.29 |
| Bank Fees | -73,790.67 | 3,562.12 |
| General Expenses | -6,590.33 | 1,075.24 |
| Postage, Freight & Courier | -1,450.42 | 218.20 |

Together these flatter FY to Feb 2026 net profit (reported 261,495.63) by
roughly 210,000. Motor Vehicle Expenses in the current year (from 1 Mar 2026)
is also a credit of 20,900.51.

Current financial year to date (1 Mar to 12 Sep 2026): income 50,000 (all
"Material Income"), no CIS labour income, no Volker activity.

## 7. Summary

- Volker owes nothing on sales. NHU owes Volker 57,473.70, possibly already
  settled by contra.
- Volker has deducted 1,876,731.20 of CIS since March 2020, of which
  826,416.68 relates to tax years 2023/24 and 2024/25 and 142,317.58 to
  2025/26 so far.
- The balance sheet suggests this CIS has been accumulating as an asset and
  not been set off or reclaimed. Confirm the CIS account balance in Xero and
  the EPS history, then get the accountant to lodge the repayment claims.
- Eight invoices charged VAT after the reverse charge date; confirm the
  treatment and that the output VAT was declared.
- Several FY to Feb 2026 expense accounts carry credit balances and need
  recoding before the accounts are finalised.
