---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API リファレンス
description: カスタム分割を伴う棒円グラフまたは円棒グラフの第2のパイまたはバーに描画されるポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ipiesplitcustompointcollection/
---
**実装されているインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

カスタム分割を伴う棒円グラフまたは円棒グラフの第2のパイまたはバーに描画されるポイントのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでチャート データポイントを取得します。 |
| [add(int dataPointIndex)](#add-int-) | 親シリーズのポイントコレクション内のインデックスでデータポイントを追加します。 |
| [remove(int dataPointIndex)](#remove-int-) | 親シリーズのポイントコレクション内のインデックスでコレクションから項目を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

インデックスでチャート データポイントを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | データポイントのインデックス。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - チャート データポイント。

### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

親シリーズのポイントコレクション内のインデックスでデータポイントを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイントコレクション内のデータポイントのインデックス。 |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

親シリーズのポイントコレクション内のインデックスでコレクションから項目を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイントコレクション内のデータポイントのインデックス。 |