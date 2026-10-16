# vps price: What a VPS Really Costs Each Month, Which Cheap Plans Are Worth It, and How RackNerd's $1.92 KVM Plan Compares

The short version: a usable VPS costs between $2 and $6 per month at most major providers, and the cheapest verified plan on the market right now is RackNerd's 512MB KVM at **$1.92/mo** — 1 vCPU, 10GB SSD, and 1TB of monthly traffic. Step up to something that can comfortably run a small website with a database and you're in the $5–$12 range.

The longer answer is more useful, because the number on the price tag is rarely the whole story. One provider's "$2" expires after three months. Another's "$8.99" locks you into a 36-month term. RackNerd, the budget outlier in every comparison, has its own quirk: its promo pages often quote yearly totals. What follows is a hand-verified February 2026 price check across the major providers, what each headline price actually commits you to, the fees that show up after checkout, and a plan-by-plan look at where RackNerd fits.

> **Quick picks**
>
> - Cheapest verified plan: RackNerd 512MB KVM at **$1.92/mo** — fine for proxies, bots, monitoring, and Linux practice; too small for a database-backed site. 👉 [Check RackNerd's current KVM plans and prices](https://bit.ly/my-rn)
> - Most hardware per euro: Contabo's €4.99 plan (4 vCPU, 8GB RAM, 50GB NVMe, unlimited traffic) and Hetzner's 4GB plans around €4–6.
> - Least effort: GoDaddy's managed VPS from $8.99/mo (first 3-year term) or IONOS, which bundles free 24/7 expert support.
> - Whatever you pick, check the billing cycle before paying — that's where the surprise usually hides.

## How much does a VPS actually cost per month?

Entry pricing at the big names clusters between $2 and $5 per month, and every provider below has a plan under $6. These are the cheapest verified plans as of February 2026:

| Provider | Entry plan | vCPU · RAM | Storage · Traffic | Price |
| --- | --- | --- | --- | --- |
| RackNerd | 512MB KVM | 1 · 512 MB | 10 GB SSD · 1 TB | $1.92/mo |
| Vultr | Regular | 1 · 512 MB | 10 GB SSD · 0.5 TB | $2.50/mo |
| OVHcloud | Starter | 1 · 2 GB | 20 GB SSD · 100 Mbps port | $3.50/mo |
| DigitalOcean | Basic | 1 · 1 GB | 25 GB SSD · 1 TB | $4/mo |
| Linode (Akamai) | Nanode 1GB | 1 · 1 GB | 25 GB · 1 TB | $5/mo |
| AWS Lightsail | 1 GB | 2 · 1 GB | 40 GB SSD | $5/mo |
| Hostinger | KVM 1 | 1 · 4 GB | 50 GB NVMe · 4 TB | $5.99/mo |
| Contabo | VPS S | 4 · 8 GB | 50 GB NVMe · unlimited | €4.99/mo |
| Hetzner | CX23 | 2 · 4 GB | 40 GB SSD · 22 TB | €5.49/mo |

Three things to read carefully in that table. Currency first: Hetzner and Contabo list prices in euros, and their value holds up even without converting — Hetzner's CX23 includes 2 vCPUs and 4GB of RAM for €5.49, while DigitalOcean's entry plan is $4 for 1GB. That's four times the memory at a comparable price. Traffic comes second: Contabo doesn't cap it and Hetzner allows 22TB, while Vultr's cheapest plan includes only 0.5TB. Locations come third: Vultr runs 32 data center regions and OVHcloud 30, against RackNerd's 10 and Hetzner's 6 — worth something if latency to your users matters.

Mid-range plans with 2–8GB of RAM run roughly $9–$20: RackNerd's 2GB KVM at $9.48, Hostinger's KVM 2 at $10.99 with 8GB, Hostinger's KVM 4 at $19.99 with 16GB, DigitalOcean's Premium AMD plans from $7 to $14. Dedicated-CPU and specialized configurations start around $42 at DigitalOcean — CPU-optimized from $42, general purpose from $63, memory-optimized from $84, storage-optimized from $131 — and GoDaddy's managed plans span $8.99 to $44.99 per month.

## RackNerd KVM plans and pricing

RackNerd's entry KVM lineup runs from $1.92 to $9.48 per month across three plans, and it's the cheapest starting point among the providers in the February 2026 check:

| Plan | vCPU · RAM | Storage | Traffic | Monthly price | Order |
| --- | --- | --- | --- | --- | --- |
| 512MB KVM | 1 · 512 MB | 10 GB SSD | 1 TB | $1.92 | [ Get the 512MB KVM plan](https://bit.ly/my-rn) |
| 1GB KVM | 1 · 1 GB | 20 GB SSD | 2 TB | $4.98 | [ Get the 1GB KVM plan](https://bit.ly/my-rn) |
| 2GB KVM | 2 · 2 GB | 40 GB SSD | 3 TB | $9.48 | [ Get the 2GB KVM plan](https://bit.ly/my-rn) |

What the specs say about who each plan is for:

- **512MB KVM ($1.92)** — a proxy or VPN endpoint, a small bot, uptime monitoring, a DNS server, or a Linux learning box. 512MB of RAM rules out a web stack with a database on top.
- **1GB KVM ($4.98)** — the practical floor for a small blog or brochure site with a lightweight database, a staging server, or one modest self-hosted app. 2TB of traffic covers a lot of small-site pageviews.
- **2GB KVM ($9.48)** — a small production site, two or three lightweight services sharing one box, or a dev/test server. DigitalOcean charges $12 for 2GB with 2TB of traffic, so RackNerd undercuts it on both price and bandwidth.

RackNerd runs 10 data center locations and carries a 4.4/5 rating with 99.9% uptime in the independent tracker's data — solid mid-pack numbers rather than class-leading ones. One billing quirk to know before you order: the same price check lists RackNerd's cheapest advertised entry price as $10.28, and its methodology note explains that RackNerd in particular advertises yearly totals rather than monthly rates. When a RackNerd promo page shows a low double-digit number, confirm whether it's an annual figure before comparing it against anything. 👉 [See RackNerd's KVM plans and current pricing](https://bit.ly/my-rn)

## Intro rates and term pricing: why some "cheap" VPS prices expire

Two of the most visible low prices in this market are temporary, and neither provider hides it — you just have to read the fine print.

IONOS currently advertises its VPS S+ at $2 per month. That rate holds for the first 3 months of a 1-year term, then renews at $6. First-year total: $60. Every year after: $72. On the larger VPS M+, the intro barely moves the bill — 3 months at $5 plus 9 months at $14 comes to $141 in year one against $168 at the regular rate. The plans themselves are respectable: NVMe storage, unlimited traffic on a 1 Gbps connection, no setup fees, a 30-day money-back guarantee, and free 24/7 expert support. Just price them at the renewal rate, and the "$2" stops distorting your comparison.

GoDaddy's $8.99 managed VPS has a different catch: the rate applies to the first 3-year term. That's 36 months of commitment at the intro price, and the plan page doesn't publish the renewal rate — get that number before signing up for three years. What the price buys is the "managed" part: automated snapshot backups, 24/7 network monitoring, DDoS protection, a free SSL certificate for the first year, and a 99.9% uptime guarantee, with configurations from 1 vCPU/2GB up to 4 vCPU/16GB at $44.99.

DigitalOcean, for contrast, just charges $4 and leaves it there — no intro rate, no term. Its Premium shared-CPU line starts at $7 for 1GB with NVMe storage, and the dedicated-CPU tiers are where premium pricing really kicks in.

## What the sticker price leaves out

The monthly rate is the floor of your bill, and four add-ons push it up:

- **Automated backups**: most providers charge 20–25% of the instance price for snapshot backups — on a $5 plan, roughly $1.00–$1.25 per month. If the workload holds data you'd hate to lose, this isn't optional.
- **Bandwidth overage**: beyond the included allowance, overage typically runs a few dollars per TB, and it can dominate the bill for media-heavy sites. OVHcloud sidesteps this by selling port speed instead of traffic quotas.
- **A domain**: about $10–15 per year if you don't already have one. TLS certificates through Let's Encrypt are free.
- **Your time**: on an unmanaged plan, patching, monitoring, and the occasional late-night recovery are on you. That's the real reason managed plans like GoDaddy's cost more, and why IONOS bundles expert support into the base price.

## Which cheap VPS is actually worth it?

On raw hardware per euro, Contabo and Hetzner lead the field — Contabo's €4.99 plan includes 8GB of RAM and unlimited traffic, and Hetzner sells 4GB plans in the €4–6 range with 22TB of traffic. Nothing else at that price comes close on specs.

RackNerd's case is different: it wins on the absolute price floor and on traffic generosity. It's the only provider in the check with a verified plan under $2, and its $9.48 plan includes 3TB of traffic where pricier rivals give you less. The independent tracker rates it 4.4/5 — behind DigitalOcean's 4.8 and Vultr's 4.7, ahead of OVHcloud's 4.2 — with 99.9% uptime matching most of the budget field.

Where RackNerd loses: base RAM (512MB versus 2–8GB elsewhere at similar money), location count (10 versus Vultr's 32), and uptime tier (99.9% versus DigitalOcean's 99.99% — about 43 minutes of monthly downtime versus about 4). If any of those matter for your project, the extra $1–3 per month at a bigger name is buying something real. If they don't, you're paying more for nothing you'll notice. 👉 [Get RackNerd's 512MB KVM plan for $1.92/mo](https://bit.ly/my-rn)

## Frequently asked questions

**Is a $2-per-month VPS actually usable?**
Yes, for the right jobs. A 512MB RAM server handles proxies, small bots, monitoring agents, DNS, and Linux practice without complaint. It will not comfortably run a database-backed website or more than a couple of services at once — that's 1–2GB territory.

**How much does a VPS for a small website cost?**
Budget $5–$12 per month. RackNerd's 1GB KVM is $4.98, Hetzner's 4GB plans sit around €4–6, AWS Lightsail's 2GB plan is $12, and DigitalOcean's 2GB Basic is also $12. If RAM is the priority, Hostinger's KVM 2 offers 8GB for $10.99.

**Can I get these prices without a long-term commitment?**
Mostly yes. Vultr, OVHcloud, DigitalOcean, Hetzner, Contabo, Linode, and the RackNerd plan rates above are all quoted monthly. The two exceptions are IONOS, whose intro rate requires a 1-year term, and GoDaddy, whose $8.99 is tied to a 3-year term.

**Does paying more get you better uptime?**
Only slightly at the budget end. The February 2026 check records 99.9% uptime for RackNerd, Hetzner, OVHcloud, Hostinger, Contabo, and Linode, 99.95% for Vultr, and 99.99% for DigitalOcean. Whether shrinking downtime from ~43 minutes a month to ~4 justifies the premium depends entirely on your project.

## Picking a plan, and two checks before you pay

Decision rules, based on the verified prices above:

- Proxy, bot, monitoring, or a Linux sandbox → RackNerd 512MB KVM at $1.92/mo.
- Small website with a lightweight database → RackNerd 1GB KVM at $4.98/mo. If you'd rather have 4–8GB of RAM at similar money, Contabo's €4.99 plan and Hetzner's 4GB plans are
