# buy ethena: ENA or USDe, how the order actually clears, and the risks worth reading first

Type "buy ethena" into a search box and you'll get a wall of "how to buy ENA" pages that all say the same four things: sign up, verify, deposit, buy. None of them tell you that two different assets sit behind that one word, that the fee you pay depends on a tier you probably don't know you're on, or that the buyback story driving most of the ENA coverage right now hasn't actually started yet.

So here's the version that skips the intro music.

## First, decide what you're actually buying

Ethena is the protocol. It runs two things that people routinely mix up:

- **ENA** — the governance token. It votes, it has a price, it moves.
- **USDe / sUSDe** — the synthetic dollar. USDe is designed to hold a peg; sUSDe is the staked version that accrues yield.

If you want the thing that goes up and down, you want ENA. If you want a yield-bearing dollar-like position, you want USDe or sUSDe, and you should not buy ENA thinking it's the same bet. Search "buy ethena" on ENA's ticker and more often than not you end up in the first camp anyway, so the rest of this piece is about ENA.

One more detail worth knowing before you click anything: ENA is an ERC-20 token on Ethereum. Before you send funds anywhere, verify the contract address against the official Ethena page. Copy-paste mistakes are how people buy the wrong token, and that mistake is not refundable.

## What ENA is, in plain terms

Ethena Labs built USDe as a synthetic dollar backed by crypto collateral and short futures hedges rather than by bank deposits. ENA launched alongside it in April 2024 and reached an all-time high of **$1.52 on April 11, 2024**. The tokenomics, as listed on Binance's asset page: 30% to core contributors, 25% to investors, 15% to the Foundation, 30% to ecosystem development, with a maximum supply of 15 billion ENA and an initial circulating supply of about 1.425 billion.

An airdrop of 750 million ENA — 5% of total supply — went to USDe users. That's a useful data point for a reason that comes up later: if you're buying ENA now because you heard there's an airdrop, you're roughly two years late. The distribution already happened.

## The buyback math everyone leads with

In September, ENA holders approved a fee switch that routes **95% of Ethena's net protocol revenue into open-market ENA purchases**. Standard Chartered initiated coverage on the back of it, with Geoffrey Kendrick forecasting in a note titled "Ethena – A scalable yield-bearing stablecoin" that ENA reaches $0.42 by end-2026, $1.10 by end-2027 and $2.00 by end-2028. At the time that note was published, ENA was trading around $0.26, so the end-2028 figure implies roughly a 7x.

The mechanism matters more than the target. The approved take rate steps up with USDe's circulating supply: 5% at $7.5 billion, 10% at $10 billion, 15% at $15 billion, 20% at $20 billion. Nothing gets bought below the first threshold.

> Per DefiLlama data cited by The Defiant, USDe supply sat around **$4.9 billion** when that coverage ran. That's roughly 53% of growth away from the first buyback purchase.

So the correct reading is: the buyback is real, approved, and scheduled — but idle. Anyone telling you ENA is being bought back right now is describing something that hasn't been switched on.

Two more things from the same reporting that belong in any honest risk list. First, Ethena's original yield engine was the crypto basis trade, which paid above 20% at points in 2024; those rates compressed, and USDe supply fell from a 2025 peak of around $15 billion. The protocol has been replacing that yield with other sources — over-collateralized DeFi lending, institutional lending through desks like Maple, liquid stablecoin holdings, credit products — for a blended figure Standard Chartered puts at about 5.2% versus a 7% average since inception. Second, remaining investor unlocks were accelerated into a single release on October 5, with about 12% of supply staying locked afterwards. If you're buying, you should know supply has been landing in the market.

## Where an ENA order actually goes through on Gate

Gate lists ENA in several forms. On the spot market it's **ENA/USDT**. There's also an ENA/USDT perpetual for leveraged trades, plus spot margin, Gate Convert for one-click swaps out of USDT or ETH, and Simple Earn and structured products if you'd rather hold ENA somewhere it does something.

The buy flow is standard, but the funding step is where the real cost differences hide.

### The five steps

1. **Create an account.** Email or phone. 👉 [👉 Open a Gate account and pull up the ENA/USDT market](https://bit.ly/GateVIP)
2. **Complete identity verification.** You need this for most funding routes and for anything beyond basic spot trading.
3. **Fund the account.** Bank transfer, card, P2P/C2C, Convert from existing crypto, an on-chain deposit, or a GateCode transfer from another Gate user.
4. **Place the order.** Search ENA in the spot market, then choose limit or market. A limit order that rests on the book is a maker order and, depending on your tier, cheaper than a market order.
5. **Check the confirmation screen.** Total cost, applicable fee, and rate are all shown before you confirm. Read it. That screen is the last place the real number appears before it's deducted.

### Funding routes and what each one costs

Gate's own buy-ENA guide lists these, with fees that vary by region and provider:

- **Card** — fastest, no prior deposit needed, roughly 1–5% per transaction.
- **Bank transfer** — SEPA, SWIFT, FPS and similar; low or zero platform fee but typically 1–3 business days to settle.
- **P2P / C2C** — you trade directly with another user under Gate's escrow; no platform trading fee, though the seller sets the price and you pay the payment provider's own fees.
- **Gate Convert** — one click from USDT or ETH into ENA. A small spread applies.
- **On-chain deposit** — send ENA or a base asset from an external wallet. Withdrawal fees are dynamic and network-dependent.

Also worth knowing up front: Gate restricts or prohibits some services in restricted regions, including the United States, Canada, Iran and Cuba. Check the current restricted list in the user agreement before you deposit, not after.

## The full fee tier table

This is the part most "how to buy" pages leave out, even though it's the number that actually hits your balance. Gate runs 17 spot tiers, and each one has a standard rate plus a lower rate if you pay fees in GT, the platform token. Here's the full published structure, reflecting the rates Gate set out for its April 9, 2026 fee adjustment.

| VIP tier | Spot maker / taker (VIP rate) | Spot maker / taker (GT payment) | Buy link |
| --- | --- | --- | --- |
| VIP 0 | 0.100% / 0.100% | 0.090% / 0.090% | [ Start at VIP 0](https://bit.ly/GateVIP) |
| VIP 1 | 0.099% / 0.099% | 0.089% / 0.089% | [ Unlock VIP 1 rates](https://bit.ly/GateVIP) |
| VIP 2 | 0.098% / 0.098% | 0.088% / 0.088% | [ Unlock VIP 2 rates](https://bit.ly/GateVIP) |
| VIP 3 | 0.097% / 0.097% | 0.087% / 0.087% | [ Unlock VIP 3 rates](https://bit.ly/GateVIP) |
| VIP 4 | 0.095% / 0.096% | 0.086% / 0.086% | [ Unlock VIP 4 rates](https://bit.ly/GateVIP) |
| VIP 5 | 0.090% / 0.095% | 0.081% / 0.085% | [ Unlock VIP 5 rates](https://bit.ly/GateVIP) |
| VIP 6 | 0.085% / 0.090% | 0.076% / 0.081% | [ Unlock VIP 6 rates](https://bit.ly/GateVIP) |
| VIP 7 | 0.080% / 0.085% | 0.070% / 0.076% | [ Unlock VIP 7 rates](https://bit.ly/GateVIP) |
| VIP 8 | 0.075% / 0.080% | 0.060% / 0.072% | [ Unlock VIP 8 rates](https://bit.ly/GateVIP) |
| VIP 9 | 0.070% / 0.075% | 0.050% / 0.068% | [ Unlock VIP 9 rates](https://bit.ly/GateVIP) |
| VIP 10 | 0.040% / 0.058% | 0.040% / 0.058% | [ Unlock VIP 10 rates](https://bit.ly/GateVIP) |
| VIP 11 | 0.030% / 0.045% | 0.030% / 0.045% | [ Unlock VIP 11 rates](https://bit.ly/GateVIP) |
| VIP 12 | 0.020% / 0.037% | 0.020% / 0.037% | [ Unlock VIP 12 rates](https://bit.ly/GateVIP) |
| VIP 13 | 0.010% / 0.030% | 0.010% / 0.030% | [ Unlock VIP 13 rates](https://bit.ly/GateVIP) |
| VIP 14 | 0.008% / 0.023% | 0.008% / 0.023% | [ Unlock VIP 14 rates](https://bit.ly/GateVIP) |
| VIP 15 | 0% / 0.020% | 0% / 0.020% | [ Unlock VIP 15 rates](https://bit.ly/GateVIP) |
| VIP 16 | 0% / 0.0175% | 0% / 0.0175% | [ Unlock VIP 16 rates](https://bit.ly/GateVIP) |

A few things in that table are worth reading twice, because they're not obvious from the headline rate.

**Maker and taker are identical for the first four tiers.** If you're at VIP 0 through VIP 3, resting a limit order on the book costs exactly the same as crossing the spread. The maker discount people talk about doesn't exist for a new account.

**GT payment stops helping at VIP 10.** At VIP 0 it saves you 0.01 percentage points on each side. From VIP 10 upward, the two columns are the same number, so holding GT to pay fees buys you nothing at the tiers where the numbers are large.

**The fee table isn't the only fee.** Gate's Alpha market charges 0.8% at every tier, shown alongside the spot rates on the same page. Perpetual futures are priced separately and much lower: **0.020% maker and 0.050% taker at VIP 0**, and the ENA/USDT perpetual is the market that matters if you're trading ENA with leverage.

### How the tier actually gets assigned

Gate evaluates accounts on 30-day trading volume and on asset and GT-holding levels, takes whichever works out better, and recalculates periodically. Volume gets weighted by product rather than counted flat: spot and Convert count at 100%, USDT perpetual, BTC perpetual and USDT delivery futures at 40%, USD1 contracts and options at 20%, and CFD contracts at 10%. Options and CFD volume therefore don't move your tier nearly as fast as spot volume does.

Representative published entry points: VIP 1 sits around **$2,000 in account assets, or 50 GT held on a 14-day average, or $60,000 in 30-day volume**. VIP 5 around $40,000 in assets, 2,000 GT, or $1,000,000 in volume. VIP 10 around $2,000,000 in assets, 100,000 GT, or $100,000,000 in volume. There's also a retention window before a downgrade takes effect, so a slow month doesn't immediately reset your rates. Check the live VIP page for your own numbers, because the thresholds are published as representative and get revised.

## What a $500 ENA order actually costs

Run the arithmetic at the tier you'll realistically start on.

A $500 market buy at **VIP 0** pays 0.100% taker: **$0.50**. Pay the fee in GT and it's 0.090%: **$0.45**. A $500 limit order that rests on the book and gets filled as maker pays the same 0.100% at VIP 0, which is the trap described above.

Now push it to VIP 5. Taker drops to 0.095% ($0.475), maker to 0.090% ($0.45). If you're a buy-and-hold buyer placing one order and closing the tab, that difference is five cents. The tier system starts to matter somewhere north of a few thousand dollars of monthly turnover, and for most people reading a "buy ethena" guide, it doesn't matter at all on the first order. What matters far more is the funding fee, because a 1–5% card fee dwarfs the 0.1% trading fee by a factor of ten to fifty.

That's the actual cost decision: fund cheaply, then trade.

## Five things people get wrong

**Buying ENA for the airdrop.** The 750 million ENA distribution to USDe users is historical. Farming it now isn't a thing.

**Treating ENA like a stablecoin.** ENA has drawn down hard from its 2024 high. USDe is the peg product. They're not interchangeable, and the ticker you type determines which risk you're taking.

**Ignoring the unlock schedule.** Investor unlocks were accelerated into one release with about 12% of supply still locked afterward, and the Nasdaq-listed ENA treasury vehicle StablecoinX holds roughly 20% of total supply under lockup terms in its SEC filings. Supply structure is a bigger swing factor than most retail buyers assume.

**Assuming the buyback is running.** It isn't. It arms at $7.5 billion of USDe supply.

**Buying on a card because it's fast.** A 1–5% card fee on a volatile asset means ENA has to appreciate meaningfully before you break even.

## The risks, without the pep talk

The bullish case here is mechanical and legible: a fee switch that routes 95% of net revenue into buying ENA on the open market, scaling as USDe grows. That's a real structure with named thresholds, not a vibe.

The bear case is equally mechanical. USDe has to grow about 53% from $4.9 billion before a single token gets bought. Yield that once came from basis trades paying over 20% now blends to roughly 5.2%, which is closer to what a decent savings product pays than to the numbers that made Ethena famous, and supply already retreated from its peak once those rates compressed. Standard Chartered's own stated risks are slower adoption of yield-bearing stablecoins and slower growth in on-chain real-world assets. And ENA is a governance token with a 15 billion max supply sitting below a $2.00 target that, even on the bank's own schedule, is two years out.

None of that says don't buy. It says know which of the two things you're buying, and why.

## FAQ

**Do I need an exchange to buy ENA?**
No. ENA is an ERC-20 token, so you can swap for it in a non-custodial wallet or on a DEX. You'll pay gas, and you'll get whatever liquidity the pool has, which on a smaller pair can be worse than a centralized order book. A centralized venue is simpler if you're funding with fiat.

**Which pairs are available for ENA on Gate?**
Spot ENA/USDT and an ENA/USDT perpetual, plus spot margin. Convert handles one-click swaps from USDT or ETH.

**Is there a minimum?**
There's no meaningful minimum on spot. Gate's own futures guide notes a minimum transfer of 0.0001 USDT into the contract account, which is a technical floor, not a practical one.

**Can I buy ENA in the US or Canada?**
Gate lists those among restricted regions in its user agreement. Confirm your own jurisdiction's status before funding an account.

**Can I earn on ENA after buying it?**
Gate offers Simple Earn and structured products, and the ENA perpetual market exists if you want to hedge or trade directionally. The perpetual's leverage is set per market; Gate's own ENA perpetual guide references up to 50x on that contract with the standard caveat that the live page governs.

**What's the single most important number before I buy?**
Not the price. The fee on your funding method. 0.1% versus 5% is the difference between a rounding error and a real headwind, and that's before ENA moves at all.

When you're ready to run it: 👉 [👉 Compare the ENA/USDT market and the full fee table on Gate](https://bit.ly/GateVIP), fund through the cheapest route available in your region, and place a limit order rather than a market order if you're not in a hurry. That's the whole playbook.
