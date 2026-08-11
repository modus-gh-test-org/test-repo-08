# Drop the unused legacy adapter

Requests could previously hang forever when the upstream stopped responding. This adds an explicit timeout and surfaces it as a typed error.

Change #4 of 4 on branch `pr/20260811-105826-4-drop-the-unused-legacy-adapter`.
