# introduction

A list of changes made to library systems for Covid-19 mitigation in June 2020 and to enable their loan collections service. 

# changes

## OLE Drools rules changes:

- OLE: Allow hold requests of REF and THREE_DAY (previously LONG and ONE_WEEK only) 
- OLE: Change due date period following a recall request to 14 days for all item types (previously 7 days)
- OLE: Change to circulation rules to allow requesting up to 5 items for all borrower types and all item types (previously 3)
- OLE: Change one week loans (ONE_WEEK item type) to loan for 14 days (previously 7 days) (CHANGE REQUEST 2020-06-11: One week loans should loan for 30 days)
- OLE: Remove all fines for books i.e. for item types ONE_WEEK, THREE_DAYS, LONG (previously 0.75 per day for ONE_WEEK, THREE_DAYS; 0.25 per day for LONG)
- OLE: Enable hold requests for items with status AVAILABLE
- OLE: Updated the circulation rules for renewals of all item types and all borrower types to up the max. number of renewals from 10 to 3000
- OLE: Updated the general check all transactions to up the fine limit from £10 to £3000

## VuFind config changes:

- VuFind: Add hold / recall link to 'all' items

 
