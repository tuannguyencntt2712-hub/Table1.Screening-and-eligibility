# Table 1 — Screening & Eligibility (PRISMA-ScR)

**Scope:** Item-level screening evidence for the manuscript’s PRISMA-ScR flow (exclusions only).  
**Freeze/Search date:** 10 July 2025

## Purpose
- Provide a transparent **screening log** of excluded records:
  - **25** exclusions at **Title–Abstract–Keywords**
  - **3** exclusions at **Full text**
- Allow readers to **verify** the PRISMA counts reported in the manuscript.

> Database-level filtering (years, source type, language, etc.) is **not** tracked here.  
> That cascade appears in **Table 1** of the manuscript.

## Files
- **PRISMA_counts.xlsx** *(optional)*  
  Stage-level counts used in the PRISMA figure (should read: **260 → 235 (−25) → 232 (−3)**).
- **Excluded/Excluded_25_Title_Abstract_Keywords.xlsx**  
  Item-level list and reasons for the 25 records excluded at title/abstract/keywords.
- **Excluded/Excluded_3_FullText.xlsx**  
  Item-level list and reasons for the 3 records excluded at full-text assessment.

### Recommended minimum columns (for both Excluded files)
- `Title` — article title  
- `DOI` — article DOI (blank if unavailable)  
- `Excluded_Reason` — short, plain-language reason  
- (Optional) `Notes`

## How to use
1. Cross-check the PRISMA figure in the manuscript against **PRISMA_counts.xlsx**:  
   **260 identified after database limits → 235 screened (−25) → 232 included (−3)**.
2. Inspect **Excluded/** spreadsheets to see item-level reasons for the **25 + 3** exclusions.
3. Cite this repository in **Methodology** as the screening log source.

## Data quality
- Keep titles non-empty; DOIs may be blank if not available.  
- Use concise, consistent reasons (plain language is fine).  
- If any exclusion status changes, update the counts file so PRISMA stays consistent.

## Versioning & citation
- Suggested tag/release: `v1.0.0-freeze-2025-07-10`.  
- Citation:  
  > Thanh Tuan, N., & Le Anh, T.(2025a). *Table1.Screening-and-eligibility* [Data set]. GitHub.

