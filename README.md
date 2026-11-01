# GMU IT & E-Learning Support — web pages

These are the public web pages for the support system. They contain **no passwords and no secrets**.
All protection (sign-in, roles, limits, validation) is applied by the Apps Script server.

| File | Purpose |
|---|---|
| `index.html` | Front page — links to the two forms |
| `ticket.html` | Online support ticket form |
| `walkin.html` | Check-in form for the support desk |
| `confirm.html` | Opened from the email buttons: confirm resolved / still an issue / rate |
| `dashboard.html` | Staff console (sign-in required) |
| `config.js` | **The one place to paste the Apps Script `/exec` address** — do not overwrite it when updating |
| `404.html` | Friendly page for a wrong address |
| `lib/` | Chart and PDF code, hosted here so nothing is ever loaded from another network (do not edit) |

Never add `Code.gs` or any password to this repository.
