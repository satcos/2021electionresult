# 2021 Assembly Election Result - India
2021 Indian assembly election results scrapped from https://results.eci.gov.in/

This script scare state assembly election results from ECI website for following states
1. Assam
2. Kerala
3. Puducherry
4. Tamil Nadu
5. West Bengal

Script is simple, It does following
- Reads master page and build constituency id and name
- Generates url for each constituency
- Query them one by one and parse the data

Parsed data is stored in csv format (One for each state) with following fields
1. cid (Constituency ID)
2. cname (Constituency Name)
3. O.S.N.
4. Candidate
5. Party
6. EVM Votes
7. Postal Votes
8. Total Votes
9. PctVotes (% Votes)

Final Data is available in Data/ directory

