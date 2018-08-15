# smarttravels
smartravels is an ethereum dApp that enables users with an ethereum address to interact and trade on last minute airline tickets that havn't been sold for specific flights. This enables customers to buy cheaper tickets.

In the future, airlines could have random dates where they sell out flight tickets this way that aren't last minute (24h) flight tickets.

#project setup
...

# rules
users should only pay in ether after the time of the sale of flight tickets run out. Needed for this is a seperate Payment Contract.

We need to check the balance of the owner's address and if it exceeds the current ticket price then it should disable the "trade" button and update the UI accordingly. If another trade happens the UI also needs to be updated. In order to do this we would need to use ---
events.

Should we simulate "other trades" when trade by the owner is made?