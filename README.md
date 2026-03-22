# sysadmin-toolkit
My personal sysadmin toolkit scripts, configs, and notes I actually use.

# Asset Tracking – Branch Office Inventory
**Enterprise Challenge Lab #1**

---

## Overview

This project documents the asset tracking setup completed for the new branch office. The goal was to inventory all shipped equipment, establish a tracking process, and implement a tool to manage assets across the team.

---

## Assets Tracked

| Category | Examples |
|---|---|
| Servers | VM Server |
| Networking Equipment | Cisco 1941 Series Router |
| Computing Peripherals | Wired Keyboard, Mouse |
| Monitors | Dell P2418HZm |
| Other Hardware | Switch, 479XF24 |

---

## Tool Used: Sortly

We chose **Sortly** as our asset tracking platform for the following reasons:

| Feature | Details |
|---|---|
| Centralized database | All assets in one place, accessible by the whole team |
| Visual tracking | Photos attached to each item for easy identification |
| Serial number tracking | Each item logged with a unique identifier |
| Status updates | Items marked as assigned, in storage, or under maintenance |
| Team collaboration | Real-time updates so everyone stays on the same page |
| Mobile-friendly | Usable from anywhere, not just a desktop |

---

## Process

**Start of shift:**
1. Check in all items
2. Confirm each asset is present and damage-free
3. Log status in Sortly

**End of shift:**
1. Check out all items
2. Confirm assets are present and no damage occurred
3. Update records in Sortly

> **Responsibility:** The designated IT Admin is accountable for completing check-in/check-out each shift. Any missing or damaged items are reported to the Office Manager immediately.

---

## Inventory Snapshot

| Item | Qty | Unit Price | Total Value |
|---|:-:|--:|--:|
| 479XF24 | 8 | $949.99 | $7,599.92 |
| Cisco 1941 Series Router | 1 | $1,000.00 | $1,000.00 |
| Switch | 1 | $90.99 | $90.99 |
| Wired Keyboard | 8 | $199.99 | $1,599.92 |
| Mouse | 8 | $8.25 | $66.00 |
| Dell P2418HZm | 8 | $236.99 | $1,895.92 |
| VM Server *(pricing TBD)* | 1 | — | — |
| **Total — 7 items / 35 units** | | | **$12,252.75** |

---
<img width="912" height="460" alt="image" src="https://github.com/user-attachments/assets/dff795c4-3c45-494c-a638-e2fced1bc70b" />

## Notes

- VM Server pricing to be confirmed and updated
- All assets tracked with photos in Sortly
- Tracker to be updated whenever assets are added, removed, or change status
