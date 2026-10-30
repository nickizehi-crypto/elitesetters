# Elite Setters – Claude guide

## ClearStats data (via Slack)

ClearStats (engine.clearstats.io) is the DiagoFit team's sales dashboard, built and run by Tes (tes@clearstats.io, Slack ID U0AR862AXPW) with Jahswill. There is no ClearStats connector, so when Nick asks for ClearStats data, get it from Slack with the Slack connector.

Slack only holds what people post there, not the live dashboard. Always give the date of the message a number came from, and say plainly when nothing recent has been posted.

### How to look

1. Search all channels with `slack_search_public_and_private`, `include_bots: true`, sorted by `timestamp`. Use keywords for the metric (e.g. `ClearStats`, `leads`, `booked`, `held`, `won`, `collected`, `"talk time"`, `"show rate"`, `commissions`) and an `after:` date filter for the period asked.
2. Then read the most likely channels below with `slack_read_channel` (and `slack_read_thread` for threads with replies).
3. If Slack has nothing for the question, offer to ask Tes in #backend-request. Only post after Nick confirms.

### Where ClearStats numbers show up

| Channel | ID | What's there |
| --- | --- | --- |
| #alex-executive-team-chat | C0AMV9V6K8X | Headline numbers and new tabs (Revenue Ops/Costs, ICP, YouTube tracking): leads, booked, held, won, cash collected |
| #diagofit-full-oversight-chat | C0C3H6V0C2V | Oversight, clipper portal |
| #backend-request | C0C0WBL7WKE | ClearStats fixes, logins, data questions to Tes/Jahswill |
| #sales-commissions-tracking | C0A6LFT98BF | Commissions |
| #trellus-diagofit | C0C9G7E25UY | SDR dialler / talk time (Trellus) |
| #low-ticket-management | C0C2YL1PKMW | Low Ticket tab: funnel, members, trials |
| #project-work | – | Setter Review Console (setter chat scores) |
| Group DM (Kaushik, Callum, Bobby, Tes, Nick) | C0BQBS4CVL5 | SDR/setter tiles, form fields |

Answer in plain language: the number, the period it covers, where it came from (channel + date + permalink), and anything that looks off.
