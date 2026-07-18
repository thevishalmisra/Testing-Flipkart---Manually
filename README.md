# Flipkart Home Page — Test Cases

Manual test case documentation for the **Home Page** module of Flipkart (flipkart.com), covering login, search, product display, and navigation elements.

## Project Details

| Field | Value |
|---|---|
| Project Name | Flipkart |
| Module Name | Home Page |
| Created By | Vishal Raman |
| Created Date | 2026-06-15 |
| Executed By | Vishal |

## Test Summary

| Metric | Count |
|---|---|
| Scenarios | 7 |
| Total Test Cases | 11 |
| Passed | 9 |
| Failed | 2 |

## Scenarios Covered

| Scenario ID | Description | Status |
|---|---|---|
| FP01 | Home page displays correctly after login with correct credentials | ✅ Pass |
| FP02 | Username is displayed on the home page, stacked with other essential options | ✅ Pass |
| FP03 | Most-selling and discounted products are displayed on the home page | ✅ Pass |
| FP04 | Search bar is present, including audio and image-based search | ⚠️ Partial (2 Fail) |
| FP05 | Products are clickable and redirect to the product specification page | ✅ Pass |
| FP06 | User profile section is available on the home page | ✅ Pass |
| FP07 | Products are displayed based on categories | ✅ Pass |

## Known Issues

- **FP04.002** — Audio search option is not yet implemented in the search bar.
- **FP04.003** — Image-based search option is not yet implemented in the search bar.

## Test Case Structure

Each test case in the source spreadsheet (`Test_cases_-_FLIPKART.xlsx`) follows this format:

| Column | Description |
|---|---|
| Scenario TID | Unique ID for the scenario (e.g., FP01) |
| Scenario Description | High-level behavior being validated |
| Test Case ID | Unique ID for the individual test case (e.g., FP01.001) |
| Pre Condition | State required before executing the test |
| Steps to Execute | Step-by-step actions performed |
| Expected Result | Anticipated outcome |
| Actual Result | Observed outcome |
| Status | Pass / Fail |
| Executed QA Name | Tester who ran the case |
| Misc (Comments) | Additional notes, e.g. unimplemented features |

## File

- `Test_cases_-_FLIPKART.xlsx` — full test case sheet with all scenarios, steps, and results.

## How to Use

1. Open `Test_cases_-_FLIPKART.xlsx` to view or update individual test cases.
2. Add new test cases following the existing Scenario TID / Test Case ID numbering convention.
3. Update the **Status**, **Actual Result**, and **Misc** columns after each execution cycle.
   - Testers explore the software to find defects that may not be covered by existing test cases. This approach involves creative and dynamic testing to uncover hidden issues.

Manual testing is suitable for various types of testing, including functional testing, integration testing, system testing, and acceptance testing. While manual testing is effective in certain scenarios, it has some limitations, such as being time-consuming for repetitive tasks and lacking the scalability of automated testing. In many cases, a combination of manual and automated testing is employed to achieve comprehensive test coverage.
