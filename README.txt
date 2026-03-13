Iran War Dashboard final corrected bundle

Replace:
- index.html
- war-data.json

Fixes included:
- ISO timestamp, so freshness parses correctly
- event log sorted newest first
- business sections grouped into Iranfarhang and KIP
- all dynamic content pulled from war-data.json
- charts extend to Mar 13
- trend lines stop at the last real non-null launch value instead of flying off into nonsense

Important:
The launch charts still show no plotted missile/drone values for Mar 10–13 because the JSON correctly leaves those as unknown, but the dashboard now handles that cleanly.
