# patent-sdc-match
These data provide a patent-deal number match, as in our working paper, Emery, L. and Woeppel, M., Patent Thickets and Mergers and Acquisitions. These data span M&A deals announced from 1980 through 2022.

If you use these data, please cite our paper (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4249384) as the data source. 

| Variable    | Description                                        |
| ----------- | -------------------------------------------------- |
| ann_date    | Deal announcement date                             |
| deal_number | Deal number from SDC                               |
| patnum      | Patent number                                      |
| acquirer    | Indicator that the patent is owned by the acquirer |
| target      | Indicator that the patent is owned by the target   |

The dataset includes all active patents we matched to companies in SDC M&A deals. Patents are assigned to firms based on ownership at the end of the year prior to the deal after accounting for all prior ownership changes.

The deal sample is restricted as follows:
- Deals must have valid effective or withdrawal dates and non-missing percent sought
- Acquirers hold less than 50% pre-deal and seek more than 50%
- Completed deals must result in more than 90% ownership
- Deal types are limited to mergers, asset acquisitions, and majority interest acquisitions
- Acquirers are U.S.-based firms

If you have any data issues or questions, please contact Mike Woeppel at mwoeppel@iu.edu.
