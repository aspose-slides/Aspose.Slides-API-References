---
title: IChartDataPointCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 시리즈 데이터 포인트의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartdatapointcollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

시리즈 데이터 포인트의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 컬렉션에서 인덱스(시리얼 번호)로 시리즈 데이터 포인트를 반환합니다. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 컬렉션에서 데이터 포인트의 인덱스(시리얼 번호)를 반환합니다. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues 속성 리스트의 값 유형을 지정합니다. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 컬렉션에 이미 해당 인덱스의 데이터 포인트가 존재하면 해당 데이터 포인트를 반환합니다. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 요소를 제거합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

컬렉션에서 인덱스(시리얼 번호)로 시리즈 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

컬렉션에서 데이터 포인트의 인덱스(시리얼 번호)를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**반환값:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceForXValues(int value)
```

데이터 포인트의 XValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.XValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

데이터 포인트의 YValue 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.YValue.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

데이터 포인트의 BubbleSize 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPointEx.BubbleSize.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**반환값:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

데이터 포인트의 Value 속성 객체에서 AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 ChartDataPoint.Value.Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues 속성 리스트의 값 유형을 지정합니다. 읽기 전용 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**반환값:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

컬렉션에 이미 해당 인덱스의 데이터 포인트가 존재하면 해당 데이터 포인트를 반환합니다. 컬렉션에 인덱스 index==N(컬렉션의 데이터 포인트 수가 N 이하인 경우) 가 없으면 부족한 데이터 포인트를 추가하고 마지막(요청된 인덱스) 데이터를 반환합니다. 예를 들어 컬렉션 인덱스가 {0, 1, 2}이고 요청 인덱스가 5이면 메서드는 부족한 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | long | 인덱스. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 요청된 인덱스의 데이터 포인트를 반환합니다.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Line 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Scatter 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Radar 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 및 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 및 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Area 하위 유형 중 하나인 경우에 적용됩니다(또는 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypePie(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Pie 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypePie(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | double | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Bubble 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xValue | java.lang.String | 데이터 포인트 XValue |
| yValue | double | 데이터 포인트 YValue |
| bubbleSize | double | 데이터 포인트 BubbleSize |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Surface 하위 유형 중 하나인 경우에 적용됩니다(예: ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 메서드 참조).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Sunburst인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 SizeValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Waterfall인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 BoxAndWhisker인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Treemap인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 SizeValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Histogram인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Funnel인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 값 |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Map인 경우에 적용됩니다.

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


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 데이터 포인트 ColorValue |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 새 데이터 포인트.

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 값. |

### removeAt(int index) {#removeAt-int-}
```
public abstract      ? (…)
```

주어진 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 데이터 포인트의 인덱스. |