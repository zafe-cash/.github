# Zafe

A shared vault for shielded Zcash. A group controls one shielded address, and a payment
goes out only when **t of the N** members approve it on their phones.

- **Private on chain:** re-randomized FROST makes one ordinary spend signature, so a
  vault looks like any single-user wallet.
- **No blind signing:** every phone rebuilds and checks the transaction before it signs.
- **Blind relay:** the server only forwards encrypted messages and can't spend.

[Website](https://zafe.cash) · [Code](https://github.com/zafe-cash/zafe) · hello@zafe.cash
