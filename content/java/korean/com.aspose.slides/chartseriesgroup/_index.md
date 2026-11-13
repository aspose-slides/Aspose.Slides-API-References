---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API 참조
description: 시리즈 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Represents group of series.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## 메서드

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 이 시리즈 그룹의 유형을 반환합니다. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 이 그룹의 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. |
| [getSeries()](#getSeries--) | 시리즈 컬렉션을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getUpDownBars()](#getUpDownBars--) | Line- 또는 Stock-chart의 상승/하강 막대에 대한 접근을 제공합니다. |
| [getGapWidth()](#getGapWidth--) | 바 또는 열 클러스터 사이의 간격을 바 또는 열 너비의 백분율로 가져오거나 설정합니다. |
| [setGapWidth(int value)](#setGapWidth-int-) | 바 또는 열 클러스터 사이의 간격을 바 또는 열 너비의 백분율로 가져오거나 설정합니다. |
| [getGapDepth()](#getGapDepth--) | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 가져오거나 설정합니다. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 가져오거나 설정합니다. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(degree) 단위로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(degree) 단위로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%에서 90% 사이 가능). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%에서 90% 사이 가능). |
| [getOverlap()](#getOverlap--) | 2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%에서 100% 사이)로 지정합니다. |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%에서 100% 사이)로 지정합니다. |
| [getSecondPieSize()](#getSecondPieSize--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%에서 200% 사이)로 지정합니다. |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%에서 200% 사이)로 지정합니다. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. |
| [getPieSplitPosition()](#getPieSplitPosition--) | 파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. |
| [getPieSplitBy()](#getPieSplitBy--) | 파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. |
| [isColorVaried()](#isColorVaried--) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [hasSeriesLines()](#hasSeriesLines--) | 차트에 시리즈 라인이 있는 경우 true. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 차트에 시리즈 라인이 있는 경우 true. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines 형식을 지정합니다. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 사용자 정의 분할이 있는 파이-오브-파이 차트 또는 바-오브-피 차트에 대한 사용자 정의 분할 정보를 제공합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |
### getType() {#getType--}
```
public final int getType()
```


이 시리즈 그룹의 유형을 반환합니다. 읽기 전용 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**반환값:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


이 그룹의 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```


시리즈 컬렉션을 반환합니다. 읽기 전용 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**반환값:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```


Line- 또는 Stock-chart의 상승/하강 막대에 대한 접근을 제공합니다. 읽기 전용 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**반환값:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


바 또는 열 클러스터 사이의 간격을 바 또는 열 너비의 백분율로 가져오거나 설정합니다. 값은 0에서 500 사이여야 합니다. 읽기/쓰기 int.

--------------------

이 속성은 다음 유형의 시리즈에 적용됩니다: Bar 하위 유형([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 메서드 참조), Column 하위 유형([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 메서드 참조), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**반환값:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```


바 또는 열 클러스터 사이의 간격을 바 또는 열 너비의 백분율로 가져오거나 설정합니다. 값은 0에서 500 사이여야 합니다. 읽기/쓰기 int.

--------------------

이 속성은 다음 유형의 시리즈에 적용됩니다: Bar 하위 유형([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 메서드 참조), Column 하위 유형([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 메서드 참조), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 가져오거나 설정합니다. 값은 0에서 500 사이여야 합니다. 읽기/쓰기 int.

--------------------

이 속성은 다음 유형의 시리즈에 적용됩니다: 3D Bar 및 Column 하위 유형([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) 메서드 참조), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**반환값:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```


3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 가져오거나 설정합니다. 값은 0에서 500 사이여야 합니다. 읽기/쓰기 int.

--------------------

이 속성은 다음 유형의 시리즈에 적용됩니다: 3D Bar 및 Column 하위 유형([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) 메서드 참조), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(degree) 단위로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). 읽기/쓰기 int.

**반환값:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```


첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(degree) 단위로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%에서 90% 사이 가능). 읽기/쓰기 byte.

**반환값:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```


도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 0%에서 90% 사이 가능). 읽기/쓰기 byte.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%에서 100% 사이)로 지정합니다. -100%: 최대 간격(막대가 완전히 분리). -0%: 겹침이나 간격 없이 나란히 배치. 100%: 최대 겹침(막대가 완전히 겹침). 이 속성은 읽기/쓰기 byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 겹침을 55%로 설정
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```


2-D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%에서 100% 사이)로 지정합니다. -100%: 최대 간격(막대가 완전히 분리). -0%: 겹침이나 간격 없이 나란히 배치. 100%: 최대 겹침(막대가 완전히 겹침). 이 속성은 읽기/쓰기 byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 겹침을 55%로 설정
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%에서 200% 사이)로 지정합니다. 읽기/쓰기 int.

**반환값:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```


파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%에서 200% 사이)로 지정합니다. 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**반환값:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```


버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**반환값:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```


두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**반환값:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```


두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```


시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```


시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


차트에 시리즈 라인이 있는 경우 true. stacked bar 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```


차트에 시리즈 라인이 있는 경우 true. stacked bar 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```


HiLowLines 형식을 지정합니다. HiLowLines는 HiLowClose, OpenHiLowClose, VolumeHiLowClose 및 VolumeOpenHiLowClose 차트 유형과 함께 적용됩니다.

**반환값:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). 읽기/쓰기 int.

**반환값:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```


버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


사용자 정의 분할이 있는 파이-오브-파이 차트 또는 바-오브-피 차트에 대한 사용자 정의 분할 정보를 제공합니다. 파이-오브-파이 차트 또는 바-오브-피 차트에서 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다. 읽기 전용 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**반환값:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
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