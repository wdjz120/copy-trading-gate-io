# copy trading gate io: start with $10, pick a leader who isn't hiding a drawdown, and know exactly what you pay

Most people typing this have already decided they want a piece of Gate's copy trading hub. The questions left are usually unglamorous ones: what's the actual minimum, does the trader take a cut of my money every day or only when I'm up, and how do I read a leaderboard without getting burned by a 30-day ROI number that hides a 60% drawdown.

Here's what those answers look like on Gate right now, including the parts the leaderboard screenshots conveniently leave out.

## What copy trading on Gate is (and isn't)

Gate's copy trading hub lives at the copy trading section of the exchange. You pick a lead trader — Gate calls them traders or lead traders — and their futures positions get mirrored into your account at a proportional size. When they open BTCUSDT long, a position appears on your side. When they close, yours closes too.

Two mechanics matter more than anything else on that page:

**Your copy money sits in a separate virtual sub-account.** Margin moves out of your spot account into a dedicated copy trading sub-account. When the copy relationship ends, the system settles that sub-account, deducts profit sharing and trading fees, and returns the remainder to spot. That separation is genuinely useful — a bad copy trade doesn't eat your spot bag.

**You choose how positions get sized.** Proportional mode scales the trader's position to your allocated capital. Fixed amount mode keeps a constant order size regardless of what the trader's portfolio looks like. Proportional is the default in smart mode, and for most followers it's the better fit, because it preserves the weights of the trader's strategy instead of flattening everything to the same ticket size.

What it isn't: a savings product, a managed fund, or anything with a floor under it. Copy trading on Gate is futures exposure with leverage. Liquidation still exists. A trader's past returns are a description of the past.

Gate has also expanded past crypto futures. Stock copy trading went live on 24 July 2026, and bot copying has been around longer. Those three products behave differently enough that they deserve their own comparison.

## The three copy products on Gate, side by side

| Copy product | What gets copied | How you're charged | Minimum to start | Access |
| --- | --- | --- | --- | --- |
| Futures copy trading | Crypto perpetual futures positions, mirrored proportionally or at fixed size | Trading fee at your VIP rate, plus the trader's profit-share rate — default 10% of positive follower PnL, settled daily | Gate's guides cite 10 USDT as the base follower floor, but each trader sets their own (10 / 50 / 100 / 300 USDT all appear in the wild) | Gate web and App: Trade → Copy Trading; App: More → Futures → Copy Trading |
| Stock copy trading | Real US, Hong Kong and Korean stocks and ETFs — 12,500+ instruments, fractional from 0.01 share | Trading fee plus High-Water Mark profit sharing: a new cut is only charged when cumulative net PnL beats the previous peak | Fractional sizing from 0.01 share, so small accounts can track expensive names | Gate App V8.29.0 or later (Copy Trading → Stocks); web was still listed as coming soon |
| Bot copy trading | Another user's trading bot configuration and parameters | Free to copy; 5% of profits goes to the bot's original creator when the bot ends | Depends on the bot strategy and its own capital settings | Bot leaderboard / bot plaza inside Gate |
|  |  |  |  |  |
| --- | --- |  |  |  |
| [Set up a Gate account and open the copy trading hub](https://bit.ly/GateVIP) | [Review Gate's futures copy trading options](https://bit.ly/GateVIP) |  |  |  |

Two things worth flagging about that table. First, the stock product's fee logic is different from the futures one — HWM means the trader only gets paid when your cumulative net PnL pushes past its previous high, so recovering a drawdown doesn't trigger a fresh cut. Futures copy doesn't carry the same documented HWM rule, which is exactly why you shouldn't assume a fee model from one product applies to the other. Second, bot copying catches people out: the 5% is paid to whoever built the bot, and copies of copies still feed the original creator.

## What you actually pay as a follower

Gate doesn't charge a subscription for copy trading. Nobody bills you a monthly fee while your position sits flat. The costs arrive in two places.

**Profit sharing.** The default rate is 10% of follower profits. Settlement runs daily at 00:00, covering the previous 24 hours — from 00:00 the day before to 00:00 that day. A share is only taken when the follower's total PnL over that window is positive. So on a losing day you pay nothing in profit share. The formula is the obvious one: net profit × share rate, deducted and rounded down.

**Trading fees.** Every mirrored open, close and partial reduce pays the standard fee for the product. At VIP 0 that's 0.02% maker and 0.05% taker on perpetual futures, and 0.10% maker / 0.10% taker on spot (or 0.09% / 0.09% if you pay fees in GT). Gate's own worked example: a market order on a $60,000 position at 0.05% taker costs $30. A limit order on the same size at 0.02% costs $12. That gap is the single easiest lever a follower controls.

Perpetual contracts also carry funding, settled every eight hours. Hold a copied position for days and funding can quietly outrun the trade fee. Nothing about copy trading removes that.

A practical gut-check on cost: if you copy a trader whose profit share is set at 20%, and your copied position turns $500 profit, the trader's cut is roughly $100 before you've counted trading fees and funding. That's the real number, not the ROI on their profile card.

## The price list Gate actually publishes

Gate doesn't sell plans. There's no Basic tier and no Pro tier — the closest thing to a pricing page is the VIP fee schedule, and it's the table that determines what copy trading costs you. Gate adjusted its spot and futures fee structure on 9 April 2026, so older screenshots floating around are out of date.

| VIP tier | Spot maker / taker | Spot maker / taker paid in GT | USDT perpetual maker / taker |
| --- | --- | --- | --- |
| VIP 0 | 0.100% / 0.100% | 0.090% / 0.090% | 0.020% / 0.050% |
| VIP 1 | 0.099% / 0.099% | 0.089% / 0.089% | 0.020% / 0.050% |
| VIP 2 | 0.098% / 0.098% | 0.088% / 0.088% | 0.020% / 0.050% |
| VIP 3 | 0.097% / 0.097% | 0.087% / 0.087% | 0.020% / 0.048% |
| VIP 4 | 0.095% / 0.096% | 0.086% / 0.086% | 0.020% / 0.048% |
| VIP 5 | 0.090% / 0.095% | 0.081% / 0.085% | 0.020% / 0.045% |
| VIP 6 | 0.085% / 0.090% | 0.076% / 0.081% | 0.018% / 0.042% |
| VIP 7 | 0.080% / 0.085% | 0.070% / 0.076% | 0.016% / 0.0375% |
| VIP 8 | 0.075% / 0.080% | 0.060% / 0.072% | 0.014% / 0.035% |
| VIP 9 | 0.070% / 0.075% | 0.050% / 0.068% | 0.012% / 0.032% |
| VIP 10 | 0.040% / 0.058% | same as VIP column | 0.010% / 0.030% |
| VIP 11 | 0.030% / 0.045% | same as VIP column | 0.008% / 0.028% |
| VIP 12 | 0.020% / 0.037% | same as VIP column | 0.006% / 0.026% |
| VIP 13 | 0.010% / 0.030% | same as VIP column | 0.005% / 0.024% |
| VIP 14 | 0.008% / 0.023% | same as VIP column | 0.002% / 0.022% |
| VIP 15 | 0% / 0.020% | same as VIP column | 0% / 0.018% |
| VIP 16 | 0% / 0.0175% | same as VIP column | 0% / 0.016% |

A few notes that matter for followers specifically:

- **Copy trading volume counts toward your VIP tier.** Gate's fee page includes spot copy trading and futures copy trading volume in the 30-day volume calculation. So copying consistently is one way to climb the ladder without adding turnover elsewhere.
- **The GT discount stops helping at VIP 10.** From that tier up, the standard and GT columns are the same number.
- **Maker fees don't split from taker until VIP 4.** At VIP 0 through VIP 3 on spot, resting an order costs the same as crossing the spread.
- **Tier counts differ between Gate's own pages.** The live fee schedule runs to VIP 16, while some Gate Learn write-ups describe the ladder as VIP 0 to VIP 14. Trust the live fee page before you plan around a threshold.

If you want to check where your account currently sits, 👉 [sign in and check your fee tier on Gate](https://bit.ly/GateVIP) — the applicable rate only shows once you're logged in.

## The minimums that actually gate you

Three different numbers get thrown around, and they apply to different people.

**Follower minimum:** Gate's guides put the floor at 10 USDT. That's the base figure, not a promise — the actual minimum is set by each trader, and Gate's own FAQ notes traders commonly set 50, 100 or 300 USDT entry points. If you have $10 and the trader you want requires $300, you're not copying them.

**Lead trader minimum:** To operate as a lead trader, Gate's documentation cites a 1,000 USDT requirement.

**Follower cap:** Traders hit a 900-follower ceiling and have to apply for an increase beyond it. Worth knowing when a profile looks popular — the cap tells you what "most followed" can mean on this platform.

## Your first copy trade, step by step

1. **Create an account** and complete verification. You'll need the account funded before any copy relationship is worth setting up. 👉 [Open your Gate account here](https://bit.ly/GateVIP)
2. **Move USDT to spot, then decide your copy budget.** Treat it as money you're prepared to lose, separate from the rest of your holdings. The sub-account structure makes this easy — just don't top it up impulsively.
3. **Open the copy trading page.** Web: Trade → Copy Trading. App: More → Futures → Copy Trading.
4. **Filter traders by what you can actually verify.** Gate exposes ROI over set periods, max drawdown, Sharpe ratio, win rate, follower count and traded pairs. A trader with a 12% 30-day ROI and 8% drawdown is a different animal from one showing 80% ROI and 55% drawdown.
5. **Set your parameters before confirming.** Allocation amount, stop-loss or maximum loss, leverage multiplier if you want it, and margin mode under advanced settings. The maximum-loss setting is the one that turns a bad month into a bad month instead of a wiped sub-account.
6. **Start and leave it alone for a while.** Constant manual tinkering is how follower returns drift away from the trader's numbers.
7. **To exit, close the copy relationship.** Positions close proportionally — partial closes on the lead's side close a proportional slice on yours, so you can wind down in stages.

## Why your returns won't match the leaderboard

This trips up nearly every new follower, so it's worth spelling out. Gate's own FAQ lists the reasons openly: different contract costs, changes in the trader's margin, inconsistent leverage, use of a copy multiplier, slippage, and shared risk limits causing a copy order to fail. Add your own stop-loss firing before the trader's exit and a funding cost you're paying on a position the trader closed hours ago.

There's also a filter question. Gate hides trader profiles for reasons including three weeks without trades, no open positions, lead trading paused manually, copy funds below the tier requirement, external promo links in the profile, high-risk activity flagged by the system, or negative returns. A profile that suddenly vanishes from search isn't a technical glitch.

## Risk machinery Gate does provide

- **Slippage protection.** If a copied execution price diverges too far from the trader's fill price, the order gets marked as a failed copy rather than filling at a nonsense price.
- **Risk limits.** A market-protection mechanism that caps maximum position size and leverage exposure, mainly to avoid mass forced liquidations in extreme conditions.
- **Proportional closes.** Partial closes on the lead side close proportional portions on the follower side.
- **Your own max-loss setting.** The only loss control that reflects your situation rather than the market's.

What none of it does is stop a bad strategy from losing money. HWM on the stock product shapes when fees trigger — it doesn't cap losses. Slippage protection prevents absurd fills — it doesn't prevent bad ones.

## If you'd rather run the other side

Becoming a lead trader is an application, not a switch. You submit from the copy trading page, verify the email tied to your account, and accept the trader terms. Gate says review typically finishes in one to two working days, with results sent by email, site message or SMS.

Two conditions to know before you apply. While your application is pending you can't follow anyone, and once approved as a lead trader you permanently lose the ability to follow other traders. If you want to both copy and lead, Gate's own guidance is to open a sub-account and apply for trader status there, so the personal-trading PnL doesn't contaminate your lead statistics.

Profit share default is 10%, adjustable once per day. Private mode gives traders custom rates and invite-only followers — Gate's help centre describes a range of 1% to 99%, while a Gate Wiki article cites up to 50% for private mode. Since the two documents disagree, check the in-app setting rather than planning around either number. Private mode also hides a trader from the public square, follower lists and rankings, though search can still surface them, and switching between public and private is limited to once per day.

## Quick answers

**Do I need 1,000 USDT to copy someone?** No. That figure is the lead trader requirement. Followers start from Gate's 10 USDT base, subject to whatever minimum the individual trader has set.

**Does Gate charge a monthly fee for copy trading?** No subscription. You pay the standard trading fee on each copied order plus the trader's profit-share rate, and profit share only applies on positive follower PnL in the daily settlement window.

**Can I copy several traders at once?** Yes, and splitting capital across traders with different styles is the standard way to avoid one strategy taking the whole account down. Just remember every copy relationship drains margin from the same sub-account pool.

**Is stock copy trading available on desktop?** Gate launched it on 24 July 2026 with App access from V8.29.0; web access was still described as coming.

**When does profit sharing get settled?** Daily at 00:00, covering the previous 24 hours. Only positive follower PnL in that window is charged.

## The short version

Gate's copy trading is cheap to try and easy to misread. There's no subscription, profit sharing only bites on profitable days in the futures product, and the follower floor starts at 10 USDT. Where people get hurt is treating a leaderboard ROI as a forecast and setting no maximum loss before hitting start.

Pick traders on drawdown and consistency rather than headline ROI, set the loss limit first, and check whether the fee model you're reading about belongs to futures copy or the HWM-based stock product. That last one alone saves a lot of confused spreadsheet work.

👉 [Start your first Gate copy trade and set your own risk limits](https://bit.ly/GateVIP)
