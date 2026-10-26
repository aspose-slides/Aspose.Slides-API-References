---
title: IChartSeriesGroup
second_title: Java API를 통한 Android용 Aspose.Slides 참조
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

1) See summary and remarks for ChartSeriesGroupCollection 클래스 and CombinableSeriesTypesGroup 열거형. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup 클래스 is read/write. Each of "series group properties" can have a read-only projection in ChartSeries 클래스.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 이 시리즈 그룹의 형식을 반환합니다. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 이 그룹의 시리즈가 보조 축에 표시되는지 여부를 나타냅니다. |
| [getSeries()](#getSeries--) | 차트 시리즈의 읽기 전용 컬렉션을 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getUpDownBars()](#getUpDownBars--) | Line- 또는 Stock-차트의 상승/하강 바에 대한 접근을 제공합니다. |
| [getGapWidth()](#getGapWidth--) | 막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. |
| [setGapWidth(int value)](#setGapWidth-int-) | 막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. |
| [getGapDepth()](#getGapDepth--) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree)로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree)로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). |
| [isColorVaried()](#isColorVaried--) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다. |
| [hasSeriesLines()](#hasSeriesLines--) | 차트에 시리즈 라인이 있는 경우 true. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 차트에 시리즈 라인이 있는 경우 true. |
| [getOverlap()](#getOverlap--) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% )로 지정합니다. |
| [setOverlap(byte value)](#setOverlap-byte-) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% )로 지정합니다. |
| [getSecondPieSize()](#getSecondPieSize--) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%에서 200% 사이 가능). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%에서 200% 사이 가능). |
| [getPieSplitPosition()](#getPieSplitPosition--) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. |
| [getPieSplitBy()](#getPieSplitBy--) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 어떻게 결정할지 지정합니다. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 어떻게 결정할지 지정합니다. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 맞춤 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 정의 분할 정보입니다. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%에서 90% 사이 가능). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%에서 90% 사이 가능). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines 형식을 지정합니다. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. |

### getType() {#getType--}
```
public abstract int getType()
```

이 시리즈 그룹의 형식을 반환합니다. 읽기 전용 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

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

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Line- 또는 Stock-차트의 상승/하강 바에 대한 접근을 제공합니다. 읽기 전용 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**반환:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. 읽기/쓰기 int.

**반환:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

막대 또는 열 클러스터 사이의 공간을 막대 또는 열 너비의 백분율로 지정합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
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

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree)로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). 읽기/쓰기 int.

**반환:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

첫 번째 파이 또는 도넛 차트 조각의 각도를 도(degree)로 가져오거나 설정합니다(위에서 시계 방향, 0에서 360도). 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
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

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

차트에 시리즈 라인이 있는 경우 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

차트에 시리즈 라인이 있는 경우 true. 스택형 막대 및 OfPie 차트에 적용됩니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% )로 지정합니다. - -100%: 최대 간격(막대가 완전히 분리됨). - 0%: 막대가 겹치거나 간격 없이 나란히 배치됨. - 100%: 최대 겹침(막대가 서로 완전히 겹침). 이 속성은 읽기/쓰기 byte입니다.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 중첩을 55%로 설정
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

2D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% )로 지정합니다. - -100%: 최대 간격(막대가 완전히 분리됨). - 0%: 막대가 겹치거나 간격 없이 나란히 배치됨. - 100%: 최대 겹침(막대가 서로 완전히 겹침). 이 속성은 읽기/쓰기 byte입니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%에서 200% 사이 가능). 읽기/쓰기 int.

**반환:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%에서 200% 사이 가능). 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**반환:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용될 값을 지정합니다. PieSplitBy 속성과 함께 사용됩니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 어떻게 결정할지 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**반환:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 어떻게 결정할지 지정합니다. 읽기/쓰기 [PieSplitType](../../com.aspose.slides/piesplittype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

맞춤 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 정의 분할 정보입니다. 읽기 전용 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**반환:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%에서 90% 사이 가능). 읽기/쓰기 byte.

**반환:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%에서 90% 사이 가능). 읽기/쓰기 byte.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). 읽기/쓰기 int.

**반환:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0%에서 300% 사이 가능). 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
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

버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**반환:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다. 읽기/쓰기 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |