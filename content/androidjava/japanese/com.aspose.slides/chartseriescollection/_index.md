---
title: ChartSeriesCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: コレクションを表します
type: docs
url: /ja/com.aspose.slides/chartseriescollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

[ChartSeries](../../com.aspose.slides/chartseries) のコレクションを表します  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [size()](#size--) | コレクション内のオブジェクト数を返します。 |
| [add(int type)](#add-int-) | 新しいチャートシリーズを作成し、コレクションに追加します。 |
| [insert(int index, int type)](#insert-int-int-) | 新しいチャートシリーズを作成し、コレクションに挿入します。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [ChartCellCollection](../../com.aspose.slides/chartcellcollection) から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 値から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 指定された [ChartSeries](../../com.aspose.slides/chartseries) を検索し、コレクション全体での最初の出現位置のゼロベースインデックスを返します。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクション内の指定された位置に格納された ActiveX コントロールを削除します。 |
| [clear()](#clear--) | コレクションからすべてのコントロールを削除します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクション全体を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定されたインデックスの要素。

### size() {#size--}
```
public final int size()
```

コレクション内のオブジェクト数を返します。読み取り専用 int。

**戻り値:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | シリーズのタイプ |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新しいチャートシリーズ。

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

新しいチャートシリーズを作成し、コレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[ChartDataCell](../../com.aspose.slides/chartdatacell) から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | シリーズ名を含むセル。 |
| type | int | シリーズの種類を設定するタイプ |

--------------------
同じセルから作成されたチャートシリーズがすでにコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。 |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズ、またはすでにコレクションに存在するシリーズ。

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[ChartCellCollection](../../com.aspose.slides/chartcellcollection) から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | シリーズ名を含むセルのコレクション。 |
| type | int | シリーズの種類を設定するタイプ |

--------------------
同じセルから作成されたチャートシリーズがすでにコレクションにある場合、メソッドは何も追加せず、そのインデックスを返します。 |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズ、またはすでにコレクションに存在するシリーズ。

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

値から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | シリーズ名。 |
| type | int | シリーズの種類を設定するタイプ |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズ。

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

指定された [ChartSeries](../../com.aspose.slides/chartseries) を検索し、コレクション全体での最初の出現位置のゼロベースインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | チャートシリーズの値。 |

**戻り値:**
int - 値が CollectionBase 全体に存在する場合の最初の出現位置のゼロベースインデックス。見つからない場合は -1。

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

指定された値を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 値。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクション内の指定された位置に格納された ActiveX コントロールを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するコントロールのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのコントロールを削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - コレクションを反復できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - コレクション全体の java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクション全体を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列 |
| index | int | 対象配列内のインデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object