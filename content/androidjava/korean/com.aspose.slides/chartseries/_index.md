---
title: ChartSeries
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: 차트 시리즈를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartseries/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

차트 시리즈를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [getExplosion()](#getExplosion--) | 파이 차트에서 열린 파이 조각이 중심에서 떨어진 거리는 파이 직경의 백분율로 표시됩니다. |
| [setExplosion(int value)](#setExplosion-int-) | 파이 차트에서 열린 파이 조각이 중심에서 떨어진 거리는 파이 직경의 백분율로 표시됩니다. |
| [getSmooth()](#getSmooth--) | 곡선 평활화를 나타냅니다. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 곡선 평활화를 나타냅니다. |
| [getName()](#getName--) | 시리즈 이름을 반환합니다. |
| [getDataPoints()](#getDataPoints--) | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. |
| [getType()](#getType--) | 이 시리즈의 유형을 반환합니다. |
| [setType(int value)](#setType-int-) | 이 시리즈의 유형을 반환합니다. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | 시리즈의 형식을 반환합니다. |
| [getOrder()](#getOrder--) | 시리즈의 순서를 반환합니다. |
| [setOrder(int value)](#setOrder-int-) | 시리즈의 순서를 반환합니다. |
| [getLabels()](#getLabels--) | 시리즈의 라벨을 반환합니다. |
| [getTrendLines()](#getTrendLines--) | 시리즈 추세선의 컬렉션. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 시리즈의 X 방향 ErrorBars를 나타냅니다. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 시리즈의 Y 방향 ErrorBars를 나타냅니다. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 이 시리즈와 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | 3D 막대 차트 시리즈의 모양을 지정합니다. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3D 막대 차트 시리즈의 모양을 지정합니다. |
| [getInvertIfNegative()](#getInvertIfNegative--) | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 시리즈에 대한 반전된 단색을 지정합니다. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 시리즈 인덱스와 차트 스타일을 기반으로 자동 색상을 반환합니다. |
| [getShowInnerPoints()](#getShowInnerPoints--) | 내부 포인트를 나타냅니다. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 내부 포인트를 나타냅니다. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 이상값 포인트를 나타냅니다. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 이상값 포인트를 나타냅니다. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 평균 마커를 나타냅니다. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 평균 마커를 나타냅니다. |
| [getShowMeanLine()](#getShowMeanLine--) | 평균 선을 나타냅니다. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 평균 선을 나타냅니다. |
| [getQuartileMethod()](#getQuartileMethod--) | 사분위 방법을 나타냅니다. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 사분위 방법을 나타냅니다. |
| [getShowConnectorLines()](#getShowConnectorLines--) | 연결선을 나타냅니다. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 연결선을 나타냅니다. |
| [getParentLabelLayout()](#getParentLabelLayout--) | 상위 카테고리 라벨의 레이아웃을 나타냅니다. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 상위 카테고리 라벨의 레이아웃을 나타냅니다. |
| [hasUpDownBars()](#hasUpDownBars--) | 라인 또는 주식 차트에 상/하 바가 있는지 여부를 결정합니다. |
| [getGapWidth()](#getGapWidth--) | 막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. |
| [getGapDepth()](#getGapDepth--) | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(°) 단위로 지정합니다(위쪽에서 시계 방향, 0~360도). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90% 사이). |
| [getOverlap()](#getOverlap--) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율로 지정합니다(-100%~100%). |
| [getSecondPieSize()](#getSecondPieSize--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%~200% 사이). |
| [hasSeriesLines()](#hasSeriesLines--) | 이 시리즈 및 관련 시리즈에 시리즈 라인이 있는지 여부를 결정합니다. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 버블 차트에서 버블 크기 값을 표현하는 방식을 지정합니다. |
| [getPieSplitPosition()](#getPieSplitPosition--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. |
| [getPieSplitBy()](#getPieSplitBy--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 사용자 정의 분할이 있는 파이-오브-파이 차트 또는 바-오브-파이 차트의 사용자 정의 분할 정보. |
| [isColorVaried()](#isColorVaried--) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 버블 차트의 배율 인수를 지정합니다(기본 크기의 0~300% 사이). |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

부모 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환값:**  
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

파이 차트에서 열린 파이 조각이 중심에서 떨어진 거리는 파이 직경의 백분율로 표시됩니다. 읽기/쓰기 int.

**반환값:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

파이 차트에서 열린 파이 조각이 중심에서 떨어진 거리는 파이 직경의 백분율로 표시됩니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

곡선 평활화를 나타냅니다. 라인 차트 또는 스캐터 차트에서 곡선 평활화가 켜져 있는 경우 true. 라인과 스캐터(선으로 연결) 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

곡선 평활화를 나타냅니다. 라인 차트 또는 스캐터 차트에서 곡선 평활화가 켜져 있는 경우 true. 라인과 스캐터(선으로 연결) 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

시리즈 이름을 반환합니다. 읽기 전용 [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**반환값:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**반환값:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

이 시리즈의 유형을 반환합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**반환값:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

이 시리즈의 유형을 반환합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

이 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. 읽기 전용 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**반환값:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

시리즈의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환값:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

시리즈의 순서를 반환합니다. 읽기/쓰기 int.

**반환값:**  
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

시리즈의 순서를 반환합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

시리즈의 라벨을 반환합니다. 읽기 전용 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**반환값:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

시리즈 추세선의 컬렉션. 읽기 전용 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

TrendLines는 비스택 2-D 영역, 막대, 열, 라인, 주식, XY(스캐터) 및 버블 차트의 데이터 시리즈에 대해 사용 가능하며, 스택형 또는 3-D 차트에서는 사용할 수 없습니다. 또한 레이더, 파이, 서피스, 도넛 차트에서도 사용할 수 없습니다.

**반환값:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

시리즈의 X 방향 ErrorBars를 나타냅니다. 읽기 전용 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

ErrorBars는 X 방향에 대해 영역, 막대, 스캐터 및 버블 시리즈에 사용 가능합니다. 다른 차트 유형에서는 이 속성이 null을 반환합니다(3D 차트 포함). 사용자 지정 값을 사용할 경우 DataPoints 컬렉션을 사용해 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성으로 값을 지정하십시오.

**반환값:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

시리즈의 Y 방향 ErrorBars를 나타냅니다. 읽기 전용 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

ErrorBars는 Y 방향에 대해 영역, 막대, 라인, 스캐터 및 버블 시리즈에 사용 가능합니다. 다른 차트 유형에서는 이 속성이 null을 반환합니다(3D 차트 포함). 사용자 지정 값을 사용할 경우 DataPoints 컬렉션을 사용해 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성으로 값을 지정하십시오.

**반환값:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

이 시리즈와 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환값:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. 읽기 전용 [IMarker](../../com.aspose.slides/imarker).

**반환값:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

3D 막대 차트 시리즈의 모양을 지정합니다. 이 속성 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [ChartShapeType](../../com.aspose.slides/chartshapetype).

**반환값:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3D 막대 차트 시리즈의 모양을 지정합니다. 이 속성 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [ChartShapeType](../../com.aspose.slides/chartshapetype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

시리즈에 대한 반전된 단색을 지정합니다. 색상 설정을 적용하려면 series format의 FillType을 FillType.Solid으로 설정하십시오. 읽기/쓰기 [ColorFormat](../../com.aspose.slides/colorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

시리즈 인덱스와 차트 스타일을 기반으로 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 사용됩니다.

**반환값:**  
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

내부 포인트를 나타냅니다. BoxAndWhisker 차트에서 내부 포인트가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

내부 포인트를 나타냅니다. BoxAndWhisker 차트에서 내부 포인트가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

이상값 포인트를 나타냅니다. BoxAndWhisker 차트에서 이상값 포인트가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

이상값 포인트를 나타냅니다. BoxAndWhisker 차트에서 이상값 포인트가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에서 평균 마커가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에서 평균 마커가 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

평균 선을 나타냅니다. BoxAndWhisker 차트에서 평균 선이 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

평균 선을 나타냅니다. BoxAndWhisker 차트에서 평균 선이 표시되는 경우 true. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다.

**반환값:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

연결선을 나타냅니다. Waterfall 차트에만 적용됩니다.

**반환값:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

연결선을 나타냅니다. Waterfall 차트에만 적용됩니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

상위 카테고리 라벨의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다.

**반환값:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

상위 카테고리 라벨의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

라인 또는 주식 차트에 상/하 바가 있는지 여부를 결정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하십시오. 형식 및 서식은 ParentSeriesGroup.UpDownBars 속성을 사용합니다. 읽기 전용 boolean.

이것은 ParentSeriesGroup.UpDownBars.HasUpDownBars 속성의 투사입니다.

**반환값:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

이것은 ParentSeriesGroup.GapWidth 속성의 투사입니다.

**반환값:**  
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

이것은 ParentSeriesGroup.GapDepth 속성의 투사입니다.

**반환값:**  
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(°) 단위로 지정합니다(위쪽에서 시계 방향, 0~360도). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

이것은 ParentSeriesGroup.FirstSliceAngle 속성의 투사입니다.

**반환값:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90% 사이). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 byte.

이것은 ParentSeriesGroup.DoughnutHoleSize 속성의 투사입니다.

**반환값:**  
byte

### getOverlap() {#getOverlap--}
```
public final boolean hasUpDownBars()
```

2D 차트에서 막대와 열이 겹치는 정도를 백분율로 지정합니다(-100%~100%). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하십시오. 읽기 전용 byte.

Overlap는 막대와 열이 너비의 백분율로 겹치거나 간격을 두는 정도를 지정합니다:
- -100%: 최대 간격(막대가 완전히 분리됨)
- 0%: 간격 없이 나란히 배치
- 100%: 최대 겹침(막대가 완전히 겹침)

이것은 ParentSeriesGroup.Overlap 속성의 투사입니다.

**반환값:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%~200% 사이). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

이것은 ParentSeriesGroup.SecondPieSize 속성의 투사입니다.

**반환값:**  
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

이 시리즈 및 관련 시리즈에 시리즈 라인이 있는지 여부를 결정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하고, 값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하십시오. 시리즈 라인의 서식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용합니다. 읽기 전용 boolean.

이것은 ParentSeriesGroup.HasSeriesLines 속성의 투사입니다.

**반환값:**  
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

버블 차트에서 버블 크기 값을 표현하는 방식을 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하십시오.

이것은 ParentSeriesGroup.BubbleSizeRepresentation 속성의 투사입니다.

**반환값:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하십시오. 읽기 전용 double.

이것은 ParentSeriesGroup.PieSplitPosition 속성의 투사입니다.

**반환값:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [PieSplitType](../../com.aspose.slides/piesplittype).

1) 이것은 ParentSeriesGroup.PieSplitBy 속성의 투사입니다. 2) 속성 값이 PieSplitType.Custom인 경우 ParentSeriesGroup.PieSplitCustomPoints 속성으로 사용자 정의 분할 정보를 정의할 수 있습니다.

**반환값:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

사용자 정의 분할이 있는 파이-오브-파이 차트 또는 바-오브-파이 차트의 사용자 정의 분할 정보. 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 읽기 전용 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

이것은 ParentSeriesGroup.PieSplitCustomPoints 속성의 투사입니다.

**반환값:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하십시오. 읽기 전용 boolean.

이것은 ParentSeriesGroup.IsColorVaried 속성의 투사입니다.

**반환값:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

버블 차트의 배율 인수를 지정합니다(기본 크기의 0~300% 사이). 이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투사이며, 따라서 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하십시오.

이것은 ParentSeriesGroup.BubbleSizeScale 속성의 투사입니다.

**반환값:**  
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation)