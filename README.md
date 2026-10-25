# GZ Zürich – family & kids programme (monthly snapshot)

A monthly snapshot of the offers for **Familien** and **Kinder** of four Zürcher
Gemeinschaftszentren: GZ Affoltern, GZ Buchegg, GZ Oerlikon and GZ Seebach.

- **Source:** [gz-zh.ch](https://gz-zh.ch), the programme pages of each GZ.
- **Updated:** automatically on the 1st of each month around 03:00 (Europe/Zurich), plus
  occasional manual runs.
- **File:** `data/zhgz-YYYY-MM-DD.csv`, where the date is the crawl date (ISO 8601). Only the
  newest file is kept.
- **Coverage:** from the crawl date to the end of the following month.
- **Format:** UTF-8 CSV with a header row and **one row per date**. Columns include `date`,
  `start`, `end` and `recurrence` (`single`, `multiday`, `weekly`, `biweekly`, `monthly`,
  `multiple`). `url` links to the offer.

## Attribution

All event information is © **Zürcher Gemeinschaftszentren** (Stiftung ZGZ, Zürich) and is
published here with their permission, for private use. For details, registration and contacts,
always use the `url` of each offer. Contact details and organiser names are removed on purpose.

The data may be out of date or incomplete. The official source is gz-zh.ch.
