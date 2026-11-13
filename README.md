# USA VPS: what a plan really costs, which configuration fits your project, and what changes the total after the first term

JustHost lists a USA VPS from $1.99 a month and tops out at $22.35 for a machine with 4 cores and 8 GB of RAM on a twelve-month term. Those figures come straight from the order page. What sits behind them is a billing model most comparison pages skip: the cheap end assumes a year paid up front, IONOS's $2 tier lasts three months before the $6 list price returns, and Hostinger's $6.49 entry plan takes $155.76 in a single payment.

Below is the full JustHost lineup, what each provider's monthly number actually covers, the add-ons that sit outside the plan price, and a configuration rule for a blog, a WooCommerce store, an API or a game server.

## Which plan fits most projects

Four tiers cover nearly every case.

- **Static page, landing page, tunnel endpoint:** the $1.99 VPS Promo gives you 1 core and 512 MB of RAM. Fine for nginx and a static build. Too little for WordPress with MySQL and a control panel on top.
- **Small WordPress site, blog, VPN:** Sirius at $3.88/mo on a 12-month term, with 1 core, 1 GB RAM, 20 GB NVMe and a 300 Mbps port. For 83 cents a month more than New Star you get double the disk and three times the port speed, which matters more than core count at this size.
- **WooCommerce, multi-site, a plugin-heavy install:** Double Star at $5.67/mo (2 cores, 2 GB, 20 GB NVMe) or Vega at $10.75 (2 cores, 4 GB, 80 GB). Take Vega if the catalogue is large or you run a page builder plus caching plus analytics.
- **API, SaaS backend, database:** Rigel at $22.35/mo, 4 cores, 8 GB RAM, 200 GB NVMe, 750 Mbps.

👉 See the full JustHost USA VPS lineup with current 12-month pricing

## Every JustHost USA VPS plan, side by side

The rows below are the full set on the JustHost VPS tariff page at the time of writing. The price column shows the discounted rate for paying twelve months up front, with the list price in brackets. Every plan uses NVMe storage and a fair-share port; the figure after the port is the monthly volume JustHost equates it to.

| Plan | vCPU / RAM | NVMe / port | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB | 5 GB / 10 Mbps (4+ TB) | $1.99/mo | [ Order VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB | 10 GB / 100 Mbps (31+ TB) | $3.05/mo ($3.81) | [ Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 core / 1 GB | 20 GB / 300 Mbps (93+ TB) | $3.88/mo ($4.85) | [ Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB | 30 GB / 300 Mbps (93+ TB) | $5.53/mo ($6.92) | [ Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB | 20 GB / 200 Mbps (62+ TB) | $5.67/mo ($7.08) | [ Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB | 40 GB / 400 Mbps (124+ TB) | $7.19/mo ($8.99) | [ Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB | 30 GB / 300 Mbps (93+ TB) | $7.84/mo ($9.80) | [ Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 cores / 4 GB | 80 GB / 500 Mbps (155+ TB) | $10.75/mo ($13.44) | [ Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB | 120 GB / 750 Mbps (232+ TB) | $14.64/mo ($18.30) | [ Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |
| Rigel | 4 cores / 8 GB | 200 GB / 750 Mbps (232+ TB) | $22.35/mo ($27.94) | [ Order Rigel](https://justhost.asia/en/services/vps/tariffs/rigel?ref=196392) |

Two things worth noticing in that table. Bright Star and Vega cost almost the same, but one gives you four cores and 30 GB while the other gives two cores and 80 GB. Cores help with concurrent PHP workers; disk helps with media libraries and database growth. Pick by which one you are short of. And Sirius costs less than Bright Star while offering the same port speed, so the entry tier is not a downgrade in network terms.

## What "$X a month" hides

IONOS advertises a USA VPS at $2/month for three months with a one-year term. After that the plan reverts to $6/month. Across the twelve months you are contracted for, that VPS S+ costs 3 × $2 + 9 × $6 = $60, an average of $5 a month. The pattern repeats up the range: VPS M+ at $5 then $14 comes to $141 in year one, and VPS XL+ at $14 then $47 comes to $389.

Hostinger's $6.49 for KVM 1 is a 24-month rate billed as one payment of $155.76. The page also states the renewal: $11.99/mo for the same term, so years three and four cost $287.76. KVM 2 runs $8.79/mo on the same basis, $210.96 upfront, renewing at $14.99.

Contabo quotes €4.40/month for CLOUD VPS 4, described as the effective monthly rate for a 12-month subscription including applicable taxes, for the first 24 months. Two years at that rate is €105.60, and the page does not state what happens in month 25.

JustHost's discount is the simplest of the four: $3.05 instead of $3.81 on New Star, $5.67 instead of $7.08 on Double Star, $22.35 instead of $27.94 on Rigel, conditional on paying twelve months at once. No separate promo code, no three-month cliff.

None of these figures is comparable at face value. A three-month promotional rate, a 24-month prepayment and a 12-month discount are three different products. If you only compare the big number on the pricing card, you will pick the one that costs most in year two.

👉 Check the 12-month rate on the Double Star plan

Currency adds another layer. IONOS and Hostinger price in dollars and both note that state and local sales taxes may apply at checkout. Contabo prices in euros with tax included, and accepts payment in USD, EUR and GBP. On a small plan, a 20% tax difference outweighs the gap between two neighbouring tiers.

## What the plan price leaves out

Control panels and extra IPs turn a cheap VPS into an average one faster than any upgrade.

IONOS charges $6/month for Plesk Obsidian, $5/month for each additional IPv4 beyond the one included, and from $0.065/GB/month for Cloud Backup. Domains start at $1/year. Every server ships with one IPv4, one IPv6/80 block and two mailboxes of 2 GB each.

HostFinch's add-ons are steeper. LiteSpeed runs $38.99/month for one CPU and $66.99 for four. Nginx with cPanel is $69.99/month, CloudLinux $16.99/month, an extra IPv4 $5.00/month. On the $52.99 plan, the panel licence can cost more than the server.

JustHost's tariff page prices the server and the port; it does not show a control panel price in the plan listing. If your stack depends on cPanel or Plesk, confirm whether the licence is included or billed separately before you pay. A $6 to $15 monthly licence on a $3.88 plan is a 150% to 380% increase, and that changes the decision far more than a dollar of plan price.

## Unmetered is not uncapped

JustHost sells port speed, not a traffic counter. The $1.99 plan has a 10 Mbps fair-share port, which the page equates to 4+ TB a month; Rigel's 750 Mbps port is quoted as 232+ TB. The port is the real ceiling. A 10 Mbps link running flat out all month moves a few terabytes, and "unmetered" does not change the arithmetic.

Contabo takes a different route: unlimited inbound and outbound, with fair usage policies that let it throttle servers showing exceptionally high or disruptive usage. OVHcloud advertises unlimited traffic at up to 3 Gbps unmetered, excluding Asia-Pacific data centres. Hostinger publishes hard numbers of 4 TB, 8 TB, 16 TB and 32 TB depending on the plan.

For a content site, the port speed decides how many concurrent downloads you can serve before pages queue. A 100 Mbps port handles roughly 12 MB/s; a 750 Mbps port handles roughly 90 MB/s. If your peak is a release download or a video file, that difference shows up in load time long before any monthly quota does.

👉 Compare port speeds across the JustHost plans

## How the alternatives line up

| Provider | Entry US configuration | Price | Billing catch |
| --- | --- | --- | --- |
| IONOS | VPS S+ 1 vCore / 2 GB / 60 GB NVMe | $2/mo, then $6 | 1-year term, 3-month promo |
| Hostinger | KVM 1 1 vCPU / 4 GB / 50 GB NVMe | $6.49/mo | $155.76 upfront, renews $11.99 |
| Contabo | CLOUD VPS 4 4 vCPU / 8 GB | €4.40/mo | 12-month term, first 24 months, tax included |
| HostFinch | US-VPS-1 1 core / 2 GB / 40 GB SSD | $7.99/mo | panels and LiteSpeed billed separately |
| OVHcloud | VPS USA | not published on the US page | unlimited traffic to 3 Gbps |

IONOS is the only provider in this group that states a 30-day risk-free trial. The others do not publish a refund window on their US VPS pages, so get the cancellation terms in writing before you pay.

Contabo's US footprint is the most specific of the five: Seattle, St. Louis (US Central) and Carlstadt, New Jersey, with pings quoted from 3 ms. Its four plan tiers run from 4 vCPU / 8 GB at €4.40 to 18 vCPU / 96 GB at €39.20, all on the same 12-month effective rate for the first 24 months.

Hostinger includes free weekly backups, a malware scanner, a managed firewall and a browser terminal on every plan, and lets you switch data centre location after purchase. That is a genuine operational advantage if your audience might move.

## Where the servers sit

JustHost's tariff page does not list data centre cities. Public write-ups of the service describe tests run on a Los Angeles node and mention one-click switching between locations after purchase. Since the plan page itself does not publish the city list, check the location selector during configuration and confirm the city you need is offered for the plan you picked.

This matters most for game servers and real-time APIs. A West Coast node serves California and East Asia well; a Central or East Coast node reaches more of the US population at low latency. If your users are spread across the country, the location choice affects perceived speed more than the difference between 2 and 4 GB of RAM.

## Before you order

Five items to confirm on the checkout page, in this order:

1. The renewal price, not just the first-term price.
2. The term length and the exact amount charged today.
3. Whether tax is added at checkout. IONOS and Hostinger both flag state and local sales tax.
4. Whether your control panel is included or billed monthly.
5. Whether the port speed covers your peak traffic, not your average.

Then match the plan to the job. A static site or a tunnel endpoint runs fine on 512 MB to 1 GB. WordPress and WooCommerce want 2 vCPU and 2 to 4 GB, with Vega or Capella if the store carries thousands of SKUs. An API, a SaaS backend or a database wants 4 vCPU and 8 GB, which on this lineup means Rigel. A game server wants a US-local node first and RAM second, so settle the location before you settle the tier.

👉 Pick the plan that matches your workload
