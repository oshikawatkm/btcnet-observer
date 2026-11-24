# btcnet-observer

Bitcoin ノードのうち、P2P のネットワーク機能だけを持つ観測ノード。
ブロックもトランザクションも検証せず、保存せず、中継しない。相手のノードに 1 ピアとしてつながり、相手が送ってくるものを記録する。

regtest のラボ（btcnet-lab）のノードと、実ネットワークのノードを観測する。

要件は [docs/requirements.md](docs/requirements.md) にある。実装はまだ始めていない。

## ライセンス

[MIT](LICENSE)
