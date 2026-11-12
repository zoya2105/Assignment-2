Atempt before AI

Initial observations:


| Potential issue |	Planned decision |	Reasoning |
|---|---|---|
Missing price values |	Investigate the missing entries and consider replacing them with the median price of the same product, if sufficient data is available.	| This would preserve the observation without allowing unusually high or low values to distort the replacement.
Inconsistent number formatting |	Standardize all price entries into a numerical format. |	Consistent formatting is necessary for calculations and statistical analysis.
Unusually high prices |	Investigate extreme values before deciding whether to retain or remove them. |	An extreme value could represent a genuine observation or a data-entry error, so removing it immediately could affect the results.
Inconsistent product names |	Standardize capitalization and spelling across product labels. |	This prevents identical products from being treated as separate categories during analysis.
Duplicate records |	Check whether repeated rows are genuine duplicates and remove confirmed duplicates. |	Duplicate observations could artificially influence averages and other statistical measures.
Inconsistent data types |	Convert relevant columns into appropriate data types. |	This ensures that numerical calculations and comparisons can be performed correctly.

