---
title: PieSplitCustomPointCollection
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: カスタム分割を持つバー・オブ・パイまたはパイ・オブ・パイ チャートの分割ポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/piesplitcustompointcollection/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

カスタム分割を持つバー・オブ・パイまたはパイ・オブ・パイ チャートの分割点のポイントのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのチャート データ ポイントを返します。 |
| [add(int dataPointIndex)](#add-int-) | 親シリーズのポイントコレクション内のインデックスでデータポイントを追加します。 |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | コレクションにデータポイントを追加します。 |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | コレクションから項目を削除します。 |
| [remove(int dataPointIndex)](#remove-int-) | 親シリーズのポイントコレクション内のインデックスでコレクションから項目を削除します。 |
| [clear()](#clear--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からすべての項目を削除します。 |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。 |
| [size()](#size--) | チャート データ ポイントの数を取得または設定します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期のルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

指定されたインデックスのチャート データ ポイントを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | インデックス。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - チャート データ ポイント。

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

親シリーズのポイントコレクション内のインデックスでデータポイントを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイントコレクション内のデータポイントのインデックス。 |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

コレクションにデータポイントを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 追加先のデータポイント。 |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

コレクションから項目を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 削除対象のデータポイント。 |

**戻り値:**
boolean - 項目が正常に削除された場合は true、それ以外の場合は false。項目が System.Collections.Generic.List\{T\} に見つからなかった場合も false を返します。

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

親シリーズのポイントコレクション内のインデックスでコレクションから項目を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataPointIndex | int | 親シリーズのポイントコレクション内のデータポイントのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) からすべての項目を削除します。

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) に項目が見つかった場合は true、そうでない場合は false。

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列です。配列はゼロベースのインデックスを持つ必要があります。 |
| arrayIndex | int | コピーを開始する配列内のゼロベースインデックス。 |

### size() {#size--}
```
public final int size()
```

チャート データ ポイントの数を取得または設定します。読み取り専用 int。

**戻り値:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。読み取り専用 boolean。

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true、そうでない場合は false。

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期のルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - コレクション全体の java.util.Iterator。