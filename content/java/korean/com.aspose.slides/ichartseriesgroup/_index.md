---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API 참조
description: 시리즈 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartseriesgroup/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

시리즈 그룹을 나타냅니다.

--------------------

1) ChartSeriesGroupCollection 클래스와 CombinableSeriesTypesGroup 열거형에 대한 요약 및 참고 사항을 확인하십시오. 2) 시리즈 그룹은 그룹에 있는 각 시리즈에 공통되는 일부 시리즈 속성을 포함합니다 ("series group properties"). "Series group properties"는 ChartSeriesGroup 클래스에서 읽기/쓰기 가능합니다. "series group properties" 각각은 ChartSeries 클래스에서 읽기 전용 투영을 가질 수 있습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 이 시리즈 그룹의 유형을 반환합니다. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 이 그룹의 시리즈가 보조 축에 표시되는지 여부를 나타냅니다. |
| [getSeries()](#getSeries--) | 차트 시리즈의 읽기 전용 컬렉션을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [getUpDownBars()](#getUpDownBars--) | Line- 또는 Stock-차트의 상/하 바에 대한 액세스를 제공합니다. |
| [getGapWidth()](#getGapWidth--) | 막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. |
| [setGapWidth(int value)](#setGapWidth-int-) | 막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. |
| [getGapDepth()](#getGapDepth--) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(0에서 360도, 위에서 시계 방향)으로 가져오거나 설정합니다. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(0에서 360도, 위에서 시계 방향)으로 가져오거나 설정합니다. |
| [isColorVaried()](#isColorVaried--) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [hasSeriesLines()](#hasSeriesLines--) | 차트에 시리즈 라인이 있으면 true. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 차트에 시리즈 라인이 있으면 true. |
| [getOverlap()](#getOverlap--) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. |
| [getSecondPieSize()](#getSecondPieSize--) | 파이오파이 차트 또는 바오파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 파이오파이 차트 또는 바오파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. |
| [getPieSplitPosition()](#getPieSplitPosition--) | 파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. |
| [getPieSplitBy()](#getPieSplitBy--) | 파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 사용자 지정 분할이 있는 파이오파이 또는 바오피 차트에 대한 사용자 지정 분할 정보. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90%). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90%). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 버블 차트의 축척 인자를 지정합니다(기본 크기의 0%~300%). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 버블 차트의 축척 인자를 지정합니다(기본 크기의 0%~300%). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines 형식을 지정합니다. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 버블 차트에서 버블 크기 값을 표시하는 방법을 지정합니다. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 버블 차트에서 버블 크기 값을 표시하는 방법을 지정합니다. |

### getType() {#getType--}
```
public abstract int getType()
```

이 시리즈 그룹의 유형을 반환합니다. 읽기 전용 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**반환:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

이 그룹의 시리즈가 보조 축에 표시되는지 여부를 나타냅니다. 읽기 전용 boolean.

**반환:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

차트 시리즈의 읽기 전용 컬렉션을 반환합니다. 읽기 전용 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**반환:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Line- 또는 Stock-차트의 상/하 바에 대한 액세스를 제공합니다. 읽기 전용 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**반환:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. 읽기/쓰기 int.

**반환:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다. 읽기/쓰기 int.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. 읽기/쓰기 int.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(0에서 360도, 위에서 시계 방향)으로 가져오거나 설정합니다. 읽기/쓰기 int.

**반환:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

첫 번째 파이 또는 도넛 차트 슬라이스의 각도를 도(0에서 360도, 위에서 시계 방향)으로 가져오거나 설정합니다. 읽기/쓰기 int.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. 읽기/쓰기 boolean.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

차트에 시리즈 라인이 있으면 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

차트에 시리즈 라인이 있으면 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. -100%: 최대 간격(막대가 완전히 분리됨). -0%: 겹침이나 간격 없이 나란히 배치. 100%: 최대 겹침(막대가 서로 완전히 겹침). 이 속성은 읽기/쓰기 byte입니다.

**반환:**
byte
--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 오버랩을 55%로 설정합니다
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

2D 차트에서 막대와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다. -100%: 최대 간격(막대가 완전히 분리됨). -0%: 겹침이나 간격 없이 나란히 배치. 100%: 최대 겹침(막대가 서로 완전히 겹침). 이 속성은 읽기/쓰기 byte입니다.
--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 오버랩을 55%로 설정합니다
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

파이오파이 차트 또는 바오파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. 읽기/쓰기 int.

**반환:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

파이오파이 차트 또는 바오파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율(5%~200%)로 지정합니다. 읽기/쓰기 int.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**반환:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

파이오파이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용할 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

파이오피이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**반환:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

파이오피이 또는 바오피 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

사용자 지정 분할이 있는 파이오피이 또는 바오피 차트에 대한 사용자 지정 분할 정보. 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다. 읽기 전용 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**반환:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90%). 읽기/쓰기 byte.

**반환:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%~90%). 읽기/쓰기 byte.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

버블 차트의 축척 인자를 지정합니다(기본 크기의 0%~300%). 읽기/쓰기 int.

**반환:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

버블 차트의 축척 인자를 지정합니다(기본 크기의 0%~300%). 읽기/쓰기 int.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines 형식을 지정합니다. HiLowLines는 HiLowClose, OpenHiLowClose, VolumeHiLowClose 및 VolumeOpenHiLowClose 차트 유형에 적용됩니다.

**반환:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

버블 차트에서 버블 크기 값을 표시하는 방법을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**반환:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

버블 차트에서 버블 크기 값을 표시하는 방법을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |