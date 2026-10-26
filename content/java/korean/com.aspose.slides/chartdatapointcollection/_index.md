---
title: ChartDataPointCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 시리즈 데이터 포인트의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartdatapointcollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

시리즈 데이터 포인트의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 컬렉션에서 인덱스(이 컬렉션에서의 일련 번호)로 시리즈 데이터 포인트를 반환합니다. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 이 컬렉션에서 데이터 포인트의 인덱스(일련 번호)를 반환합니다. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues 속성 목록에 있는 값들의 유형을 지정합니다. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 컬렉션에 이미 해당 인덱스의 데이터 포인트가 존재하면 그 데이터 포인트를 반환합니다. |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소의 개수를 가져옵니다. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 주어진 인덱스에 있는 요소를 제거합니다. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

컬렉션에서 인덱스(시리즈 내 일련 번호)로 시리즈 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

데이터 포인트의 인덱스(일련 번호)를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**반환값:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제로 사용되는지를 지정합니다. 다시 말해 ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues 속성 목록에 있는 값들의 유형을 지정합니다. 읽기 전용 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**반환값:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

컬렉션에 이미 해당 인덱스의 데이터 포인트가 존재하면 그 데이터 포인트를 반환합니다. 컬렉션에 인덱스 index==N인 데이터 포인트가 없을 경우(N은 컬렉션에 포함된 데이터 포인트 수보다 작거나 같음) 부족한 데이터 포인트를 추가하고 마지막(요청한 인덱스) 데이터 포인트를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청 인덱스가 5이면 메서드는 부족한 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | long | 인덱스. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 요청된 인덱스의 데이터 포인트를 반환합니다.

### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 복사 대상 배열. |
| arrayIndex | int | 복사를 시작할 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되는지를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 전체 컬렉션에 대한 java.util.Iterator.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다([ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 X값 |
| yValue | double | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 데이터 포인트 X값 |
| yValue | double | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 X값 |
| yValue | double | 데이터 포인트 Y값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 버블 크기 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 버블 크기 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 X값 |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Y값 |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 버블 크기 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 X값 |
| yValue | double | 데이터 포인트 Y값 |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 버블 크기 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 데이터 포인트 X값 |
| yValue | double | 데이터 포인트 Y값 |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 버블 크기 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 메서드도 참조).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Sunburst인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 SizeValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Treemap인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 SizeValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 BoxAndWhisker인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Waterfall인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Histogram인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Funnel인 시리즈에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 Value |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Map인 시리즈에 적용됩니다.

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


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 ColorValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 값. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

주어진 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 데이터 포인트의 인덱스. |