# Mortality-Risk-Score

This risk score can be used to risk stratify patients with repaired tetralogy of Fallot. Input parameters are:
Age (in years)
Body mass index (dichotimized based on BMI < 30 kg/m2 or >= 30 kg/m2)
RVESVi (in mL/m2)*
Repair type (transannular patch, RV-PA conduit, or other)
BVGFI (unitless)**

* Note that RVESVi requires BSA (calculated by the Haycock formula)
** Note that the BVGFI equation is:
  GFI=100 x  (EDV-ESV)/(1/2 (EDV+ESV)+(ventricular mass)/1.05)  
 	BVGFI=(RVGFI+LVGFI)

Using these inputs, a final risk score is output. 10-year mortality risk based on risk scores is shown in the manuscript. 
A risk score >= 4 is considered high-risk, and a risk score < 4 is considered low risk.
