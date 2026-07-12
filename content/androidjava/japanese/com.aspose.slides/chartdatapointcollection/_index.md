---
title: ChartDataPointCollection
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: シリーズ データポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/chartdatapointcollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

シリーズ データポイントのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックス（このコレクション内のシリアル番号）によってシリーズ データポイントを返します。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | このコレクション内のデータポイントのインデックス（シリアル番号）を返します。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues プロパティ リスト内の値の型を指定します。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | コレクションに既にインデックス index のデータポイントが含まれている場合、そのデータポイントを返します。 |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | 指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 新しいデータポイントを作成し、コレクションの末尾に追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

インデックス（このコレクション内のシリアル番号）によってシリーズ データポイントを返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

このコレクション内のデータポイントのインデックス（シリアル番号）を返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**戻り値:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.XValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

データポイントの XValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.XValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.YValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

データポイントの YValue プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.YValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.BubbleSize.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

データポイントの BubbleSize プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.BubbleSize.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

データポイントの Value プロパティ オブジェクトで AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが有効かを指定します。別の言い方をすれば、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues プロパティ リスト内の値の型を指定します。読み取り専用 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**戻り値:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

コレクションに既にインデックス index のデータポイントが含まれている場合、そのデータポイントを返します。コレクションに index==N のデータポイントが存在しない（コレクション内のデータポイント数が N 以下）場合、不足しているデータポイントを追加し、最後の（要求されたインデックスを持つ）データポイントを返します。例として、コレクションのインデックスが {0, 1, 2} で、要求されたインデックスが 5 の場合、メソッドは {0, 1, 2, 3, 4, 5} を追加し、インデックス 5 のデータポイントを返します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | long | インデックス。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 要求されたインデックスのデータポイントを返します。

### size() {#size--}
```
public final int size()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

指定された配列にコピーします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | コピー先の配列。 |
| arrayIndex | int | コピー開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

コレクションへのアクセスが同期されているか（スレッドセーフ）を示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

同期ルートを返します。読み取り専用 Object。

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

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Stock 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイントの Value。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Stock 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイントの Value。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Line 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイントの Value。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Line 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイントの Value。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | double | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | double | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Scatter 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | double | データポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Radar 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Radar 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Column または Bar 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) および [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Column または Bar 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) および [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Area 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Area 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Pie 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Pie 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Doughnut 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Doughnut 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Bubble 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データポイント XValue |
| yValue | double | データポイント YValue |
| bubbleSize | double | データポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Surface 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Surface 系列のサブタイプである場合に適用できます（[ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) メソッドも参照）。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Sunburst 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント SizeValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Treemap 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント SizeValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが BoxAndWhisker 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IHistogram 



```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Waterfall 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Histogram 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Funnel 系列の場合に適用できます。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント Value |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

新しいデータポイントを作成し、コレクションの末尾に追加します。チャートタイプが Map 系列の場合に適用できます。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データポイント ColorValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータポイント。

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

指定された値を削除します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 値。 |

### removeAt(int index) {#removeAt-int-}
```
public final



```

指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するデータポイントのインデックス。 |