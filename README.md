# OpenCHJ-Aozora
青空文庫所収のテキストにUniDicによる短単位の形態論情報を付与し、誤りを修正したものです。

## 2025/03/03 作品一覧
このデータは[総合研究大学院大学日本語言語科学コース](https://www.soken.ac.jp/prog/jls/)の2024年度の授業 **言語資源学演習1** の中で作られました。

| 作品名 | 作者 | 青空文庫 | 形態論情報整備・主担当 | 副担当 | 形態論情報バージョン |
|--------|------|--------------------|------------------|------|------------------|
| 走れメロス | 太宰治 | [図書カード](https://www.aozora.gr.jp/cards/000035/card1567.html) | 小木曽智信 | 謝正科 | 0.8 |
| 羅生門 | 芥川龍之介 | [図書カード](https://www.aozora.gr.jp/cards/000879/card127.html) | 久保柾子 | 木下瞳 | 0.8 |
| 高瀬舟 | 森鴎外 | [図書カード](https://www.aozora.gr.jp/cards/000129/card691.html) | 謝正科 | 呉子凡 | 0.8 |
| 注文の多い料理店 | 宮沢賢治 | [図書カード](https://www.aozora.gr.jp/cards/000081/card43754.html) | 木下瞳 | 久保柾子 | 0.8 |
| 山月記 | 中島敦 | [図書カード](https://www.aozora.gr.jp/cards/000119/card624.html) | 呉子凡 | 小木曽智信 | 0.8 |
| トロッコ | 芥川龍之介 | [図書カード](https://www.aozora.gr.jp/cards/000879/card43016.html) | 小木曽智信 | 久保柾子 | 0.8 |

元のテキストデータの作成（入力・校正）者についてはリンク先の図書カードを参照してください。

## ファイル形式
- UTF-8 (BOMなし) LF改行, タブ区切り
- フィールド（左から）
  - ファイル名（作者 作品名）
  - サブコーパス名
  - 開始文字位置（ファイル頭からのオフセット値*10）
  - 終了文字位置（同上）
  - 文境界（B=文頭）
  - 書字形出現形（=キー, 表層形）
  - 語彙素
  - 語彙素読み
  - 品詞
  - 活用型
  - 活用形
  - 発音形
  - 語種

## 形態論情報ライセンス
- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

- テキストデータのライセンスは[青空文庫の記述](https://www.aozora.gr.jp/guide/kijyunn.html)に従ってください。

## データサンプル
```
太宰治 走れメロス	OH_SC青空文庫	10	30	B	走れ	走る	ハシル	動詞-一般	五段-ラ行	命令形	ハシレ	和
太宰治 走れメロス	OH_SC青空文庫	30	60	I	メロス	メロス	メロス	名詞-固有名詞-人名-一般			メロス	固
太宰治 走れメロス	OH_SC青空文庫	60	80	B	太宰	ダザイ	ダザイ	名詞-固有名詞-人名-姓			ダザイ	固
太宰治 走れメロス	OH_SC青空文庫	80	90	I	治	オサム	オサム	名詞-固有名詞-人名-名			オサム	固
太宰治 走れメロス	OH_SC青空文庫	90	120	B	メロス	メロス	メロス	名詞-固有名詞-人名-一般			メロス	固
太宰治 走れメロス	OH_SC青空文庫	120	130	I	は	は	ハ	助詞-係助詞			ワ	和
太宰治 走れメロス	OH_SC青空文庫	130	150	I	激怒	激怒	ゲキド	名詞-普通名詞-サ変可能			ゲキド	漢
太宰治 走れメロス	OH_SC青空文庫	150	160	I	し	為る	スル	動詞-非自立可能	サ行変格	連用形-一般	シ	和
太宰治 走れメロス	OH_SC青空文庫	160	170	I	た	た	タ	助動詞	助動詞-タ	終止形-一般	タ	和
太宰治 走れメロス	OH_SC青空文庫	170	180	I	。	。		補助記号-句点				記号
太宰治 走れメロス	OH_SC青空文庫	180	200	B	必ず	必ず	カナラズ	副詞			カナラズ	和
太宰治 走れメロス	OH_SC青空文庫	200	210	I	、	、		補助記号-読点				記号
太宰治 走れメロス	OH_SC青空文庫	210	230	I	かの	彼の	カノ	連体詞			カノ	和
太宰治 走れメロス	OH_SC青空文庫	230	250	I	邪智	邪知	ジャチ	名詞-普通名詞-一般			ジャチ	漢
太宰治 走れメロス	OH_SC青空文庫	250	270	I	暴虐	暴虐	ボウギャク	名詞-普通名詞-形状詞可能			ボーギャク	漢
太宰治 走れメロス	OH_SC青空文庫	270	280	I	の	の	ノ	助詞-格助詞			ノ	和
太宰治 走れメロス	OH_SC青空文庫	280	290	I	王	王	オウ	名詞-普通名詞-一般			オー	漢
太宰治 走れメロス	OH_SC青空文庫	290	300	I	を	を	ヲ	助詞-格助詞			オ	和
太宰治 走れメロス	OH_SC青空文庫	300	320	I	除か	除く	ノゾク	動詞-一般	五段-カ行	未然形-一般	ノゾカ	和
太宰治 走れメロス	OH_SC青空文庫	320	350	I	なけれ	ない	ナイ	助動詞	助動詞-ナイ	仮定形-一般	ナケレ	和
太宰治 走れメロス	OH_SC青空文庫	350	360	I	ば	ば	バ	助詞-接続助詞			バ	和
太宰治 走れメロス	OH_SC青空文庫	360	380	I	なら	成る	ナル	動詞-非自立可能	五段-ラ行	未然形-一般	ナラ	和
太宰治 走れメロス	OH_SC青空文庫	380	390	I	ぬ	ず	ズ	助動詞	助動詞-ヌ	終止形-一般	ヌ	和
太宰治 走れメロス	OH_SC青空文庫	390	400	I	と	と	ト	助詞-格助詞			ト	和
太宰治 走れメロス	OH_SC青空文庫	400	420	I	決意	決意	ケツイ	名詞-普通名詞-サ変可能			ケツイ	漢
太宰治 走れメロス	OH_SC青空文庫	420	430	I	し	為る	スル	動詞-非自立可能	サ行変格	連用形-一般	シ	和
太宰治 走れメロス	OH_SC青空文庫	430	440	I	た	た	タ	助動詞	助動詞-タ	終止形-一般	タ	和
太宰治 走れメロス	OH_SC青空文庫	440	450	I	。	。		補助記号-句点				記号
```
