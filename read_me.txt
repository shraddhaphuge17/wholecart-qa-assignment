# WholeCart B2B Marketplace : QA Testing Assignment   #

1. Project Overview

This repository contains the manual testing deliverables for the WholeCart B2B marketplace application as part of the QA testing assignment for the Senior QA Automation Engineer role at Cidroy Infotech.

The objective was to validate key business workflows, identify defects, verify expected application behavior against the provided requirements, and document findings with reproducible steps and supporting evidence.

 2. Application Under Test

- **Application:** WholeCart B2B Marketplace
- **Testing Type:** Manual Functional Testing
- **Test Environment:** Provided WholeCart test environment
- **Test Approach:** Requirement-based testing
- **Browsers and Environment:** Record the browser and environment used during testing.

3. Scope of Testing

The following areas were covered:

- Catalogue search and category filtering
- Out-of-stock product visibility
- Cart quantity limits and empty-cart behavior
- Minimum order value per seller
- Delivery fee threshold
- Tax calculation and rounding
- Duplicate checkout prevention
- Multi-seller checkout
- Order cancellation and status visibility
- Refund and exchange quantity limits
- Additional order, invoice, delivery, and access-control scenarios where tested

 4. Repository Contents

| File / Folder | Description |
|---|---|
| `defect-log.xlsx` | Detailed defect log with reproduction steps, expected and actual results, severity, and evidence references |
| `evidence/` | Screenshots supporting observed defects and test results |

5. Defect Summary

The testing identified issues requiring investigation in areas including:

- Visibility of zero-stock products in the buyer catalogue
- Search results and category-filter behavior
- Minimum order value configuration
- Potential duplicate checkout behavior
- Seller cancellation visibility in the buyer's order history

The defect log distinguishes confirmed defects from findings that require further verification. Only reproducible and verified issues should be considered confirmed defects.

 6. Test Execution Results

Reported defect includes steps to reproduce the behavior, expected and actual results, severity assessment, and supporting evidence where available.

 7. Evidence

Screenshots are organized in the `evidence/` directory. Evidence filenames reference their associated defect IDs to make review easier.

 8. Conclusion

This repository presents the testing approach, execution results, observed issues, and supporting evidence for the WholeCart B2B marketplace. The objective is to provide clear, reproducible findings and an organized record of functional test coverage.

