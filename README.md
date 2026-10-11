# Sahni optional barcode food data

Public food-data downloads for Sahni. Users choose a region inside the app; lookup then works locally and offline. These files are not bundled with the app.

| Region | Products | Download | Installed |
|---|---:|---:|---:|
| United States | 407,401 | 20.67 MB | 74.33 MB |
| Israel | 1,133 | 0.07 MB | 0.19 MB |
| Europe | 1,916,368 | 95.92 MB | 270.01 MB |

Israel and Europe use Open Food Facts data under ODbL/DbCL; US data uses USDA FoodData Central under CC0. See [dataset licenses](LICENSE-DATA.md). The entire derived databases are supplied as release assets.

Coverage is incomplete. Israel has only 1,133 usable products in this snapshot; a missing product or nutrient remains unknown. Country tags describe contributor-reported sales regions, not barcode-prefix country. Values must be checked against the package before logging. Mass/volume basis can be inferred from package quantity; these records are marked accordingly.

Open Food Facts was downloaded on October 11, 2026. This is a download date, not a claim that every product was updated that day. USDA source release: April 30, 2026.

The manifest lists uncompressed/compressed SHA-256 hashes and exact sizes. Files use raw DEFLATE containing read-only SQLite meta/products tables. Downloads contain only public product facts; no Sahni application source, credentials, photos, personal food logs, or experiment/Health data is included.

Downloading uses GitHub HTTPS hosting. GitHub receives the requesting IP address and requested file; see [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Sahni does not send scanned barcodes, photos, Health values or meal logs for lookup.

Latest manifest: https://github.com/sabaaziz991-hash/sahni-food-data/releases/latest/download/manifest.json

Source archive checksums used to build these data:
```
f72687ee8bc6522054fe69dbfda6b91902c16af1ec2e043cde27bc6c29ad8176  off_products.csv.gz
57b0f122e61cf2840f03c11e9520275d0d2018dc036e16273fcd3cd370db2256  fdc_branded_json_2026-04-30.zip
```
