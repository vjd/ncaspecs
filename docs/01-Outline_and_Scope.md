# Introduction

This document describes the software requirements for an R package suitable for the calculation of pharmacokinetic parameters using (pre)clinical data.

## Scope

The scope of the requirements is to calculate pharmacokinetic parameters:

* both after single-dose and multiple-dose administration;
    * for multiple-dose administration, both at steady-state and not at steady-state;
* both after intravenous and extravascular administration;
    * for intravenous, after a bolus, short-duration infusion, or continuous infusion;
* both plasma and excretion-related (e.g. urine and feces) measurements;
* with or without unscheduled samples included;
* after proper handling of <LOQ values according to several different LOQ handling rules;
* after correction of deviations from nominal sampling times where possible;
* after substitution/imputation of missing observations where possible;
* after identification of data points or subjects to omit.

## Out of scope

At this time the validation does not include specifications to:

* PK parameters for breast milk, exhalation, and other more exotic measurements;
* sparse sample collection calculations;
* create any tables or figures suitable for inclusion in any document/report;
* perform any descriptive or comparative statistics on the calculated pharmacokinetic parameters.

These specifications may be added to a future version of the requirements document.
