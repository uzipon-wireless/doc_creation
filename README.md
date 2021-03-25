# 文書作成のポイント

## はじめに
- 自分の文書作成力を向上させるために得た知見を記載しています。
- 主な目的は個人の備忘録です。(結果的に誰かの参考になれば幸いです)

## この記事を読んで得られること
- PREP法で書かれた参考文書が分かる
- 参考文書が具体的にどんな構成と私が解釈したか分かる 

## 参考文書
- [Raspberry pi 4 でNAS（openmediavault）を構築する方法]( https://qiita.com/zono_0/items/1eb877ad9c6e5ac12532)

## 文書構成
- 参考文書の構成は以下と解釈した。

| 構成 | 見出し | ポイント |
| :--- | :--- | :--- |
| タイトル| XXで○○を△△する方法 | 何を伝えたいか？ |
| P(総論) | はじめに | どんな経緯で、誰に何を伝えたいと考えたか？ |
| R(利得) | この記事を読んでできること | 何を達成できることか？ |
| E(証拠) | 必要なもの | TD |
| E(証拠) | Raspbian Buster Liteの入手 | TD |
| E(証拠) | microSDカードのフォーマット | TD |
| E(証拠) | microSDカードへOSイメージの書き込み（所要時間：15分） | TD |
| E(証拠) | Raspberry Pi のSSH有効化の設定 | TD |
| E(証拠) | microSDカード の完成 | TD |
| E(証拠) | Raspberry Piの起動 | TD |
| E(証拠) | SSHクライアントでRaspberry Piに接続 | TD |
| E(証拠) | ネットワーク疎通確認 | TD |
| E(証拠) | RaspberryPiのセットアップ | TD |
| E(証拠) | openmediavaultのセットアップ | TD |
| E(証拠) | GUI（openmediavault）へアクセス | TD |
| E(証拠) | イーサネットの追加 | TD |
| P(結論) | おわりに | TD |

## タイトル

    - Raspberry pi 4 でNAS（openmediavault）を構築する方法
  


## はじめに (総論、P)
    - Raspberry Pi4を手に入れたので、さっそくイメージファイル「OMV_4_Raspberry_Pi_2_3_3Plus_4.img.xz」からNAS（openmediavault）化しようとしたら、どうやらRaspberry Pi4では動かないぽかったので、[公式（英語）の手引き](https://github.com/OpenMediaVault-Plugin-Developers/docs/blob/master/Adden-B-Installing_OMV5_on_an%20R-PI.pdf)をまねて、Raspberry Pi 4 でNAS（openmediavault）を構築する方法を、自分自身への備忘録を兼ねて、お伝えしたいと思います。
    - 参考：[公式（英語）の手引き](https://github.com/OpenMediaVault-Plugin-Developers/docs/blob/master/Adden-B-Installing_OMV5_on_an%20R-PI.pdf)
        - どうやら、openmediavaultバージョン5からRaspberryPiなどのシングルボードコンピュータ（[OMV 5.x for Single Board Computers](https://sourceforge.net/projects/openmediavault/files/OMV%205.x%20for%20Single%20Board%20Computers/)）の場合は、手動セットアップしてね！ってことになったみたいです
- 
- ## この記事を読んでできること(ベネフィット、R)
    - Raspberry PiでNAS（openmediavault 5.x）を構築できるようになる。
- 
- # 必要なもの (E)
- ## Raspbian Buster Liteの入手(E)
- ## microSDカードのフォーマット(E)
- 
- ## おわりに(P)
    - いかがでしたでしょうか？意外と簡単にRaspberry pi 4 でのNAS（openmediavault）を構築できたのではないかなと思います。
    - 今回の記事が、みなさまの学習の参考になれば幸いです。
