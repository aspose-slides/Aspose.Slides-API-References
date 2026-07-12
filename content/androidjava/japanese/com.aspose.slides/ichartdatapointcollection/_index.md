---
title: IChartDataPointCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: シリーズ データ ポイントのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ichartdatapointcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

シリーズ データ ポイントのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックス (このコレクション内でのシリアル番号) によってシリーズ データ ポイントを返します。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | このコレクション内のデータ ポイントのインデックス (シリアル番号) を返します。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | データ ポイントの XValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | データ ポイントの XValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | データ ポイントの YValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | データ ポイントの YValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | データ ポイントの BubbleSize プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | データ ポイントの BubbleSize プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | データ ポイントの Value プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | データ ポイントの Value プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues プロパティ リストの値の型を指定します。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | コレクションにインデックス index のデータ ポイントがすでに含まれている場合、そのデータ ポイントを返します。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 新しいデータ ポイントを作成し、コレクションの末尾に追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

インデックス (このコレクション内でのシリアル番号) によってシリーズ データ ポイントを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

このコレクション内のデータ ポイントのインデックス (シリアル番号) を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**戻り値:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

データ ポイントの XValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.XValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

データ ポイントの XValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.XValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

データ ポイントの YValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.YValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

データ ポイントの YValue プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.YValue.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

データ ポイントの BubbleSize プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.BubbleSize.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

データ ポイントの BubbleSize プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPointEx.BubbleSize.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

データ ポイントの Value プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**戻り値:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceForValues(int value)
```

データ ポイントの Value プロパティ オブジェクトで、AsCell、AsLiteralString、または AsLiteralDouble プロパティのいずれが実際に使用されているかを指定します。言い換えれば、ChartDataPoint.Value.Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues プロパティ リストの値の型を指定します。読み取り専用 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**戻り値:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

コレクションにインデックス index のデータ ポイントがすでに含まれている場合、そのデータ ポイントを返します。コレクションにインデックス index==N のデータ ポイントが含まれていない場合 (このコレクションのデータ ポイント数が N 以下の場合)、不足しているデータ ポイントを追加し、最後のデータ ポイント (要求されたインデックス) を返します。例: コレクションのインデックスが {0, 1, 2} で要求されたインデックスが 5 の場合、メソッドは不足分を追加して {0, 1, 2, 3, 4, 5} とし、インデックス 5 のデータ ポイントを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | long | インデックス。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 要求されたインデックスのデータ ポイントを返します。

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Stock サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeStock(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Line サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeLine(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値。 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | double | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | double | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Scatter サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeScatter(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | double | データ ポイント YValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Radar サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeRadar(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Column または Bar サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeColumn(ChartType) および ChartTypeCharacterizer.IsChartTypeBar(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Area サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Area サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeArea(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Pie サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Pie サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypePie(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Doughnut サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | double | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Bubble サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeBubble(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xValue | java.lang.String | データ ポイント XValue |
| yValue | double | データ ポイント YValue |
| bubbleSize | double | データ ポイント BubbleSize |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Surface サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Surface サブタイプのいずれかであるシリーズに適用できます (ChartTypeCharacterizer.IsChartTypeSurface(ChartType) メソッドも参照)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Sunburst のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント SizeValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Waterfall のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が BoxAndWhisker のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Treemap のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント SizeValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Histogram のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Funnel のシリーズに適用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイントの値 |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

新しいデータ ポイントを作成し、コレクションの末尾に追加します。chartType が Map のシリーズに適用できます。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | データ ポイント ColorValue |

**戻り値:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新しいデータ ポイント。

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

指定された値を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 値。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するデータ ポイントのインデックス。 |