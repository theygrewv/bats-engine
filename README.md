# 🦇 B.A.T.S. Engine: Blobs Against The Sky

The **B.A.T.S. Engine** is an open-source, decentralized card game protocol built on the AT Protocol. Inspired by *Cards Against Humanity*, it allows **Players** to match devious Black Card prompts with hilarious White Card responses in a verifiable, de-googled environment.

## 🛠 Technical Identity
This engine and its data are officially signed and verified by:
* **Engine DID:** `did:plc:5t5u6shyc4wwrenyzk4ok5rx`
* **Handle:** `blobs.skydrops.app`
* **Developer:** `v.skydrops.app`

## 📜 The Lexicons (The Rules of the Game)
Our data structures are organized under the `app.skydrops.bats.*` namespace. These definitions allow the game to be interoperable across the entire Atmosphere.

* **`bats.card`**: Defines the Black (prompts) and White (responses) cards.
* **`bats.play`**: Defines a single record of a Player submitting a card to a round.
* **`bats.session`**: Defines the Lobby—the digital room where the game happens.
* **`bats.score`**: Defines the final tally of **Loves** earned by a Player in a session.

## 🎮 How to Play
1. **Join a Lobby**: A Player starts a `session` and becomes the first **Card Czar**.
2. **Submit a Play**: Players submit `play` records matching their funniest White cards to the active Black card.
3. **Pick a Winner**: The Card Czar selects the winning response for that round and awards a **Love**.
4. **Final Score**: At the end of the session, a `score` record is signed, immortalizing the top Player of the round.

---
**Build. Play. Deploy. Built in Louisiana.**
