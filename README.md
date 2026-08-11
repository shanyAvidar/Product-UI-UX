# Product UI/UX

Interactive UI/UX prototypes of the **RatingIQ** hotel-reputation platform — named to match the live product modules.

Each is a standalone HTML prototype (inline CSS + JS, no build step). Open the root [`index.html`](index.html) landing page, or any module directly — the sidebars link across all four.

| Module | Folder | What it is |
|---|---|---|
| **ChainIQ** | [`chainiq/`](chainiq/) | Chain-level portfolio dashboard |
| **GuestIQ** | [`guestiq/`](guestiq/) | Per-hotel guest insights & ratings |
| **OperatingIQ** | [`operatingiq/`](operatingiq/) | Per-hotel operations / complaint insights |
| **ReplyIQ** | [`replyiq/`](replyiq/) | Automated review-response management |

## Viewing locally
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

All data shown is fictional demo data — no real guest information.
