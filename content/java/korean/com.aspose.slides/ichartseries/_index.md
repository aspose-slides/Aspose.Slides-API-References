---
title: IChartSeries
second_title: Aspose.Slides for Java API 레퍼런스
description: 차트 시리즈를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartseries/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

차트 시리즈를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getExplosion()](#getExplosion--) | 파이 차트의 중심에서 열린 파이 조각까지의 거리는 파이 직경의 백분율로 표시됩니다. |
| [setExplosion(int value)](#setExplosion-int-) | 파이 차트의 중심에서 열린 파이 조각까지의 거리는 파이 직경의 백분율로 표시됩니다. |
| [getSmooth()](#getSmooth--) | 곡선 부드러움을 나타냅니다. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 곡선 부드러움을 나타냅니다. |
| [getMarker()](#getMarker--) | 시리즈 마커를 반환합니다. |
| [getBar3DShape()](#getBar3DShape--) | 3-D 막대 차트 시리즈의 모양을 지정합니다. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D 막대 차트 시리즈의 모양을 지정합니다. |
| [getName()](#getName--) | 시리즈 이름을 반환합니다. |
| [getDataPoints()](#getDataPoints--) | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다. |
| [getType()](#getType--) | 이 시리즈의 유형을 반환합니다. |
| [setType(int value)](#setType-int-) | 이 시리즈의 유형을 반환합니다. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | 부모 시리즈 그룹을 반환합니다. |
| [getFormat()](#getFormat--) | 시리즈의 형식을 반환합니다. |
| [getOrder()](#getOrder--) | 시리즈의 순서를 반환합니다. |
| [setOrder(int value)](#setOrder-int-) | 시리즈의 순서를 반환합니다. |
| [getLabels()](#getLabels--) | 시리즈의 레이블을 반환합니다. |
| [getTrendLines()](#getTrendLines--) | 시리즈 트렌드 라인의 컬렉션 읽기 전용 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 방향 X인 시리즈의 ErrorBars를 나타냅니다. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 방향 Y인 시리즈의 ErrorBars를 나타냅니다. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | 시리즈 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | 시리즈 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | 시리즈 X 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | 시리즈 X 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | 시리즈 Y 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | 시리즈 Y 값에 대한 숫자 형식을 반환하거나 설정합니다. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | 시리즈 버블 크기에 대한 숫자 형식을 반환하거나 설정합니다. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | 시리즈 버블 크기에 대한 숫자 형식을 반환하거나 설정합니다. |
| [getInvertIfNegative()](#getInvertIfNegative--) | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 시리즈에 대한 반전 솔리드 색상을 지정합니다. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 이 시리즈와 관련된 범례 항목을 나타냅니다 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 시리즈 인덱스와 차트 스타일에 따라 자동 색상을 반환합니다. |
| [getShowInnerPoints()](#getShowInnerPoints--) | 내부 포인트를 나타냅니다. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 내부 포인트를 나타냅니다. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 이상치 포인트를 나타냅니다. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 이상치 포인트를 나타냅니다. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 평균 마커를 나타냅니다. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 평균 마커를 나타냅니다. |
| [getShowMeanLine()](#getShowMeanLine--) | 평균 마커를 나타냅니다. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 평균 마커를 나타냅니다. |
| [getQuartileMethod()](#getQuartileMethod--) | 사분위 방법을 나타냅니다. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 사분위 방법을 나타냅니다. |
| [getShowConnectorLines()](#getShowConnectorLines--) | 연결 선을 나타냅니다. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 연결 선을 나타냅니다. |
| [getParentLabelLayout()](#getParentLabelLayout--) | 부모 카테고리 레이블의 레이아웃을 나타냅니다. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 부모 카테고리 레이블의 레이아웃을 나타냅니다. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 버블 차트의 스케일 계수를 지정합니다 (기본 크기의 0~300% 사이 가능). |
| [hasUpDownBars()](#hasUpDownBars--) | 라인 차트 또는 주식 차트에 상승/하락 막대가 있는지 결정합니다. |
| [getGapWidth()](#getGapWidth--) | 막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. |
| [getGapDepth()](#getGapDepth--) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [isColorVaried()](#isColorVaried--) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [hasSeriesLines()](#hasSeriesLines--) | 이 시리즈 및 관련 시리즈에 시리즈 선이 있는지 여부를 결정합니다. |
| [getOverlap()](#getOverlap--) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. |
| [getSecondPieSize()](#getSecondPieSize--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5~200%)로 지정합니다. |
| [getPieSplitPosition()](#getPieSplitPosition--) | 파이-오브-파이 또는 바-오브-파이 차트에서 어떤 데이터 포인트가 두 번째 파이 또는 바에 포함될지 결정하기 위한 값을 지정합니다. |
| [getPieSplitBy()](#getPieSplitBy--) | 파이-오브-파이 또는 바-오브-파이 차트에서 어떤 데이터 포인트가 두 번째 파이 또는 바에 포함될지 결정하는 방법을 지정합니다. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 도넛 차트의 구멍 크기를 지정합니다 (플롯 영역 크기의 10~90% 사이 가능). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(0~360도, 위에서 시계 방향)으로 지정합니다. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 사용자 정의 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 정의 분할 정보입니다. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

파이 차트의 중심에서 열린 파이 조각까지의 거리는 파이 직경의 백분율로 표시됩니다. 읽기/쓰기 int.

**반환:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

파이 차트의 중심에서 열린 파이 조각까지의 거리는 파이 직경의 백분율로 표시됩니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

곡선 부드러움을 나타냅니다. 라인 차트 또는 스캐터 차트에서 곡선 부드러움이 켜져 있으면 true입니다. 라인 및 라인으로 연결된 스캐터 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

곡선 부드러움을 나타냅니다. 라인 차트 또는 스캐터 차트에서 곡선 부드러움이 켜져 있으면 true입니다. 라인 및 라인으로 연결된 스캐터 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

시리즈 마커를 반환합니다. 읽기 전용 [IMarker](../../com.aspose.slides/imarker).

**반환:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-D 막대 차트 시리즈의 모양을 지정합니다. 이 속성값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [ChartShapeType](../../com.aspose.slides/chartshapetype).

**반환:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-D 막대 차트 시리즈의 모양을 지정합니다. 이 속성값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다. 읽기/쓰기 [ChartShapeType](../../com.aspose.slides/chartshapetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

시리즈 이름을 반환합니다. 읽기 전용 [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**반환:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

이 시리즈의 데이터 포인트 컬렉션을 반환합니다. 읽기 전용 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**반환:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

이 시리즈의 유형을 반환합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**반환:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

이 시리즈의 유형을 반환합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

부모 시리즈 그룹을 반환합니다. 읽기 전용 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**반환:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

시리즈의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

시리즈의 순서를 반환합니다. 읽기/쓰기 int.

**반환:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

시리즈의 순서를 반환합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

시리즈의 레이블을 반환합니다. 읽기 전용 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**반환:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

시리즈 트렌드 라인의 컬렉션 읽기 전용 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**반환:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

방향 X인 시리즈의 ErrorBars를 나타냅니다. 읽기 전용 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

X 방향의 ErrorBars는 area, bar, scatter 및 bubble 유형의 시리즈에서 사용할 수 있습니다. 다른 차트 유형에서는 이 속성이 null을 반환합니다(3D 차트 포함). 사용자 지정 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정하십시오(([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성 사용).

**반환:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

방향 Y인 시리즈의 ErrorBars를 나타냅니다. 읽기 전용 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Y 방향의 ErrorBars는 area, bar, line, scatter 및 bubble 유형의 시리즈에서 사용할 수 있습니다. 다른 차트 유형에서는 이 속성이 null을 반환합니다(3D 차트 포함). 사용자 지정 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정하십시오(([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성 사용).

**반환:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

시리즈 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

시리즈 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

시리즈 X 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

시리즈 X 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

시리즈 Y 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

시리즈 Y 값에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

시리즈 버블 크기에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

시리즈 버블 크기에 대한 숫자 형식을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

시리즈에 대한 반전 솔리드 색상을 지정합니다. 색상 설정을 적용하려면 시리즈 형식 FillType을 FillType.Solid으로 설정하십시오. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

이 시리즈와 관련된 범례 항목을 나타냅니다 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**반환값:**
java.awt.Color - 시리즈의 자동 색상 java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

이상값 포인트를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

이상값 포인트를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시되는 경우 True입니다. BoxAndWhisker 차트에만 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다.

**반환값:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

사분위수 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

연결선을 나타냅니다. Waterfall 차트에만 적용됩니다.

**반환값:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

연결선을 나타냅니다. Waterfall 차트에만 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

부모 카테고리 레이블 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다.

**반환값:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

부모 카테고리 레이블 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%~300% 사이). 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하십시오.

--------------------

이는 ParentSeriesGroup.BubbleSizeScale 속성의 투영입니다.

**반환값:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Line- 또는 Stock- 차트에 상하 막대가 있는지 여부를 결정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하십시오. 상하 막대 서식을 지정하려면 ParentSeriesGroup.UpDownBars 속성을 사용하십시오. 읽기 전용 boolean.

--------------------

이는 ParentSeriesGroup.UpDownBars.HasUpDownBars 속성의 투영입니다.

**반환값:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

--------------------

이는 ParentSeriesGroup.GapWidth 속성의 투영입니다.

**반환값:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

--------------------

이는 ParentSeriesGroup.GapDepth 속성의 투영입니다.

**반환값:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

시리즈의 각 데이터 마커가 다른 색상을 갖도록 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하십시오. 읽기 전용 boolean.

--------------------

이는 ParentSeriesGroup.IsColorVaried 속성의 투영입니다.

**반환값:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

이 시리즈 및 관련 시리즈에 대한 시리즈 선이 있는지 여부를 결정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하십시오. 시리즈 선 서식을 지정하려면 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하십시오. 읽기 전용 boolean.

--------------------

이는 ParentSeriesGroup.HasSeriesLines 속성의 투영입니다.

**반환값:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. 이는 해당 시리즈뿐만 아니라 모든 상위 시리즈 그룹에 대한 투영이며 읽기 전용입니다. 값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하십시오. 읽기 전용 byte.

--------------------

Overlap는 막대와 열이 너비의 백분율로 겹치거나 간격을 두는 정도를 지정합니다:
- -100%: 최대 간격(막대가 완전히 분리됨)
- 0%: 겹치거나 간격 없이 나란히 배치
- 100%: 최대 겹침(막대가 완전히 겹침)
이는 ParentSeriesGroup.Overlap 속성의 투영입니다.

**반환값:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5~200%)로 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

--------------------

이는 ParentSeriesGroup.SecondPieSize 속성의 투영입니다.

**반환값:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 값(양)를 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하십시오. 읽기 전용 double.

--------------------

이는 ParentSeriesGroup.PieSplitPosition 속성의 투영입니다.

**반환값:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하십시오. 읽기 전용 [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) 이는 ParentSeriesGroup.PieSplitBy 속성의 투영입니다. 2) 속성 값이 PieSplitType.Custom인 경우 ParentSeriesGroup.PieSplitCustomPoints 속성을 사용하여 사용자 정의 분할 정보를 정의할 수 있습니다.

**반환값:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

도넛 차트의 구멍 크기를 플롯 영역 크기의 10%~90% 사이로 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하십시오. 읽기 전용 byte.

--------------------

이는 ParentSeriesGroup.DoughnutHoleSize 속성의 투영입니다.

**반환값:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

첫 번째 파이 또는 도넛 차트 조각의 각도를 0도에서 360도 사이(위쪽부터 시계방향)로 지정합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영이며 읽기 전용입니다. 상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하십시오. 읽기 전용 int.

--------------------

이는 ParentSeriesGroup.FirstSliceAngle 속성의 투영입니다.

**반환값:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

사용자 정의 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 정의 분할 정보를 제공합니다. 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다. 이는 해당 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 투영 속성이며 읽기 전용 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

이는 ParentSeriesGroup.PieSplitCustomPoints 속성의 투영입니다.

**반환값:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. 이는 이 시리즈뿐만 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성이며, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다. 상위 시리즈 그룹에 액세스하려면 ParentSeriesGroup 속성을 사용하십시오. 값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하십시오.

--------------------

이는 속성 ParentSeriesGroup.BubbleSizeRepresentation의 투영입니다.

**반환:**  
int