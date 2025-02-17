```dataview
TABLE file.mtime AS "Last Modified"
FROM "3 Atomic Notes"
// WHERE file.mtime >= date(2025-02-01)
SORT file.mtime DESC
```
