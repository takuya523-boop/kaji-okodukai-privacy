# 情報源リスト（巡回対象）

最終更新: 2026-08-18
発信ジャンル: 子育て / テック / ライフハック / マネー
読者: 30代の子育て夫婦（日本）

## 到達性の凡例
- **○ 直接** = URLに直接アクセスして一次情報が取れる
- **△ 検索経由** = 検索インデックス経由で見出し・要約までは取れる（本文は有料 or 未確認）
- **× 不可** = この実行環境からは到達できない。二次情報しか残らないため原則スキップ

---

## A. 育児・教育（2026-08-18 追加）
このカテゴリは「金融・テックのニュースを育児目線で解釈する」しかできなかった弱点を埋めるために追加。
乳幼児〜学齢期の実用ネタはここから取る。

| 情報源 | 取り口 | 到達性 | メモ |
|---|---|---|---|
| **リセマム** | https://resemom.jp/ ／ 最新: https://s.resemom.jp/category/education/latest/ | △ 検索経由 | 教育・子育て系の調査リリースがほぼ全部流れてくる。数字ネタの宝庫。`resemom.jp` はドメイン指定検索が通る |
| **ReseEd（リシード）** | https://reseed.resemom.jp/ | △ 検索経由 | リセマムの教育業界版。行政・文科省ネタはこちらが早い |
| **こどもとIT** | https://edu.watch.impress.co.jp/ ／ 月別: https://edu.watch.impress.co.jp/docs/news/index.html | △ 検索経由 | 家庭×AI×教育ICTの本丸。**直接アクセスはegress遮断**、ドメイン指定検索は通る |
| **ベビカム** | https://www.babycome.ne.jp/research/report/ ／ 調査隊: https://www.babycome.ne.jp/research/marketing/ | △ 検索経由 | 会員約35万人。妊娠・出産・0〜2歳のアンケートが強い。**ただし調査の実施時期が古いことが多い**（後述の注意） |
| **厚生労働省 報道発表** | 月別: https://www.mhlw.go.jp/stf/houdou/houdou_list_202608.html ／ 一覧: https://www.mhlw.go.jp/stf/houdou/index.html | △ 検索経由 | 育休給付・保育・人口動態。**制度改正は発信ネタとして実用性が最も高い** |
| （補）こども家庭庁 | https://www.cfa.go.jp/ | 未確認 | 児童手当・保育policyは今こちら所管。次回試す |
| （補）国立成育医療研究センター | https://www.ncchd.go.jp/press/ | △ 検索経由 | 子育て費用調査など。厚労省より読みやすい数字が出る |

### 育児カテゴリの取り扱い注意
1. **ベビカムは調査の実施時期を必ず確認する。** 「AIと育児に関する調査」は2024年3月実施のもので、2026年の記事として出すと事故ります。
2. **AI×育児の調査数字は出所が混在しています。** 検索では ベビカム／ベビーカレンダー（生成AI利用経験71.8%）／cozre（7割がAI利用）が混ざって出てくるので、**必ず1社に紐付けて引用すること。**
3. **長期休業明けの子どもの自殺関連**は毎年8月末に必ず出る話題です。扱う場合は相談窓口を必ず併記（24時間子供SOSダイヤル 0120-0-78310／通話料無料・24時間年中無休・保護者も相談可 https://www.mext.go.jp/a_menu/shotou/seitoshidou/1306988.htm ）。

---

## B. マネー・マーケット
| 情報源 | 取り口 | 到達性 |
|---|---|---|
| Bloomberg Markets | ドメイン指定検索 | △ 検索経由（本文有料） |
| Reuters Business | — | **× 不可**（クローラ拒否。site指定検索が400で弾かれる） |
| WSJ Tech | — | **× 不可**（検索で記事に到達できない） |
| （補）モゲチェック / LIFULL HOME'S PRESS | 住宅ローン金利 | △ 検索経由 |

## C. テック・スタートアップ
| 情報源 | 取り口 | 到達性 |
|---|---|---|
| TechCrunch | ドメイン指定検索 | △ 検索経由（RSS直は遮断） |
| Forbes（Innovation） | ドメイン指定検索 | △ 検索経由 |
| The Information | 検索 | △ 見出しのみ（本文完全有料） |
| **GitHub Trending** | https://github.com/trending | **○ 直接** |
| The Verge | — | **× 不可**（クローラ拒否） |
| Hacker News | — | **× 不可**（news.ycombinator.com / hnrss / Algolia API すべて遮断） |
| Product Hunt | https://www.producthunt.com/leaderboard/daily/YYYY/M/D | △ URLのみ（票数・詳細は取れない） |

## D. 海外トレンド
| 情報源 | 取り口 | 到達性 |
|---|---|---|
| 36氪 | 資金調達速報 https://pitchhub.36kr.com/financing-flash | △ 検索経由 |
| 百度熱捜 / 微博熱捜 | — | △ 検索経由 |
| 知乎熱榜 / 掘金 | — | △ 集約サイト経由の二次情報のみ |
| note 有料記事 | — | **× 不可**（ランキング実物に到達不可。**「スキ購入を除外」の判定は原理的にできない**） |
| Reddit 全サブレ | — | **× 不可**（r/LocalLLaMA, r/artificial, r/SaaS, r/Entrepreneur, r/ProductManagement, r/SideProject すべて。クローラ拒否＋API遮断） |

---

## 巡回のときの優先順位
1. **A（育児・教育）を最初に回す。** ここが枯れると発信が止まるため。
2. 次にマネー（家計に直撃するもの＝金利・為替・制度改正）。
3. テック/海外は「読者の得になる切り口」が立つものだけ拾う。立たないなら削る。
