# Sheet Map

This file summarizes each worksheet, its used range, sections, dependencies, and tables.

## 05
- **Used range:** A1:Y50
- **Dependencies:** companysettings, holidays, staffsettings
- **Purpose:** Daily time/attendance calculator for month 05 (rows per day with time-in/out, breaks, overtime, and derived hours).
- **Key sections:**
  - Input area: A2:M33
  - Calculation area: B3:J33
  - Output area: J3:J33
- **Tables:** None detected

## 04
- **Used range:** A1:Y50
- **Dependencies:** companysettings, holidays, staffsettings
- **Purpose:** Daily time/attendance calculator for month 04 (rows per day with time-in/out, breaks, overtime, and derived hours).
- **Key sections:**
  - Input area: A2:M33
  - Calculation area: B3:J33
  - Output area: J3:J33
- **Tables:** None detected

## companysettings
- **Used range:** A1:BH44
- **Dependencies:** None detected
- **Purpose:** Company profile and payroll setup values (registration numbers, tax IDs, payment preferences).
- **Key sections:**
  - Input area: A2:J30
  - Calculation area: (Formulas in Value columns)
  - Output area: (Used as lookup by other sheets)
- **Tables:** None detected

## staffsettings
- **Used range:** A1:AO30
- **Dependencies:** companysettings
- **Purpose:** Staff profile, statutory settings, attendance status list, and entitlements.
- **Key sections:**
  - Input area: A2:J30
  - Calculation area: (Formulas in Value columns)
  - Output area: (Used as lookup by other sheets)
- **Tables:** None detected

## perkeso
- **Used range:** A1:L67
- **Dependencies:** None detected
- **Purpose:** SOCSO (Perkeso) and EIS contribution lookup tables by wage band.
- **Key sections:**
  - Input area: A1:L67
  - Calculation area: (lookup table)
  - Output area: (used by formulas)
- **Tables:** None detected

## kwsp
- **Used range:** A1:K403
- **Dependencies:** None detected
- **Purpose:** KWSP/EPF contribution lookup table by wage band and age group.
- **Key sections:**
  - Input area: A1:K403
  - Calculation area: (lookup table)
  - Output area: (used by formulas)
- **Tables:** None detected

## shifts
- **Used range:** A1:G4
- **Dependencies:** None detected
- **Purpose:** Legacy scheduling sheet; appears unused unless referenced by formulas or validations.
- **Key sections:**
- **Tables:** None detected

## settingsarchive
- **Used range:** A1:P3
- **Dependencies:** None detected
- **Purpose:** Legacy scheduling sheet; appears unused unless referenced by formulas or validations.
- **Key sections:**
- **Tables:** None detected

## rosterpatterns
- **Used range:** A1:AG3
- **Dependencies:** None detected
- **Purpose:** Legacy scheduling sheet; appears unused unless referenced by formulas or validations.
- **Key sections:**
- **Tables:** None detected

## rosteroverrides
- **Used range:** A1:D2
- **Dependencies:** None detected
- **Purpose:** Legacy scheduling sheet; appears unused unless referenced by formulas or validations.
- **Key sections:**
- **Tables:** None detected

## holidays
- **Used range:** A1:G33
- **Dependencies:** None detected
- **Purpose:** Holiday calendar and priority list for attendance calculations.
- **Key sections:**
  - Input area: A1:G33
  - Calculation area: (lookup table)
  - Output area: (used by formulas)
- **Tables:** None detected
