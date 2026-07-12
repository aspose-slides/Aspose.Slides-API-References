---
title: IPieSplitCustomPointCollection
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: カスタム分割を使用した、バー・オブ・パイまたはパイ・オブ・パイ チャートの第2のパイまたはバーに描画されるポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ipiesplitcustompointcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

カスタム分割を使用した、バー・オブ・パイまたはパイ・オブ・パイ チャートの第2のパイまたはバーに描画されるポイントのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでチャート データ ポイントを返します。 |
| [add(int dataPointIndex)](#add-int-) | 親シリーズのポイント コレクション内のインデックスでデータ ポイントを追加します。 |
| [remove(int dataPointIndex)](#remove-int-) | 親シリーズのポイント コレクション内のインデックスでアイテムを削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

インデックスでチャート データ ポイントを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | データポイントのインデックス。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - チャート データ ポイント。

### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

親シリーズのポイント コレクション内のインデックスでデータ ポイントを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイント コレクション内のデータ ポイントのインデックス。 |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

親シリーズのポイント コレクション内のインデックスでアイテムを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイント コレクション内のデータ ポイントのインデックス.. |