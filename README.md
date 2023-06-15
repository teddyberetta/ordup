# ordup
an ordinals boost protocol

## How it works

1 ordup inscription = 1 upvote

## Specification

boost an ordinal by creating a JSON text inscription with one of the following properties:

- `inscription_number`: `number`
- `inscription_id`: `string`

You only need to choose one; the indexer will derive the other.

Any JSON inscription with one of these properties referencing a valid ordinal counts as a "+1"

## Examples

https://ordinals.com/inscription/f531fef5e3ceb6a04d03b71013158b8177a34416f23f7363c8c731e0cd229d07i0

https://ordinals.com/inscription/1bbbb85ba9ebd2e5d2a287714076b87d131d14c8a249deb04418a9ee9cd0faffi0

Both of the above inscriptions are valid boosts of the below inscription:

https://ordinals.com/inscription/70415f81ff21f1d391056c9d8d98b74af78c5b2397822e8f8cb043f9248a2518i0

## Etymology

ordup is a triple-entendre portmanteau of the words "ordinal", "upvote", and "word up".

in hip-hop, "word up" is often used as a form of acknowledgment or approval.

"Open your eyes and get wise, look alive... word up"
\- [Mobb Deep - "Survival of the Fittest"](https://www.youtube.com/watch?v=nfM43P_kIFU&ab_channel=MobbDeepVEVO)

## References

- [Daniel Krawisz - "Proof-of-Work as an Upvote System"](https://bitcoinfiles.org/t/f9e6c4f0ac7219257e1276cd23c1bff5e5088204ff4e3471786c6252fb00f01e)
