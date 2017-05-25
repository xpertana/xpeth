# XP Ethereum Project
* token name will be **xperience* points (XPP)

## Contract Primitives

* Request for Assist
* Offer Assist
* Accept Offer
* Assist Complete
* Validate Assist 
* Reward Assist Completion

Note: needs to be a mechanism where if the accepted assist does not ENGAGE with the customer in a 
specified amount of time, the assist is pulled back AND the assister is penalized with negative XP.

In general, as part of scoring an interaction, we could calculate a theoretical engagment metric which 
takes into the the averaged "time to respond" from each of the Session Turns: e.g. from Customer response
to next Agent response.

### Request for Assist (RFA)  (broadcast message)
* skill group - centralized list from Xpertana Nexus
* time needs - a time limit in terms of seconds | minutes | days...when the assist needs to start
* reward / payment amount details
* xpid of requester
* text description of request
* certification / XP requirements
* terms of payment: completion, timeliness/speed, quality (cust feedback), contribution (XPKB) 

### Offer Assist
* XPid
* Proof of cerfitication
* Eth address for remitance of payment

## Accept Assist Offer
* XP session Id (facilitate seamless transfer/handoff)

##

