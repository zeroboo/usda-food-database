# USDA Food Database (`usda-food-database`)

Public static food nutrition database curated and normalized for the Calorie Counter application.

Generated automatically by [`usda-food-database-generator`](https://github.com/zeroboo/usda-food-database-generator).

## Structure
- `food-db.json`: Normalized whole-food database (~9,000 items) for AI meal photo recognition.
- `branded/`: 2-tier prefix-sharded branded food database (~450,000 barcode items).
- `manifest.json`: Metadata, entry counts, and SHA-256 verification hash.

## CDN Usage (jsDelivr)
Clients consume pinned version tags:
```
https://cdn.jsdelivr.net/gh/zeroboo/usda-food-database@v2026.11.01/food-db.json
https://cdn.jsdelivr.net/gh/zeroboo/usda-food-database@v2026.11.01/manifest.json
https://cdn.jsdelivr.net/gh/zeroboo/usda-food-database@v2026.11.01/branded/{prefix2}/{prefix4}.json
```
