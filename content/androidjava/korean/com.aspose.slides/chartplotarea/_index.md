---
title: ChartPlotArea
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트가 플롯되어야 하는 사각형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartplotarea/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)  
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

차트가 플롯될 사각형을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 플롯 영역의 형식을 반환합니다. |
| [getX()](#getX--) | 플롯 영역 경계 상자의 왼쪽 위 모서리의 x 좌표를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. |
| [setX(float value)](#setX-float-) | 플롯 영역 경계 상자의 왼쪽 위 모서리의 x 좌표를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. |
| [getY()](#getY--) | 플롯 영역 경계 상자의 왼쪽 위 모서리의 y 좌표를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. |
| [setY(float value)](#setY-float-) | 플롯 영역 경계 상자의 왼쪽 위 모서리의 y 좌표를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. |
| [getWidth()](#getWidth--) | 플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. |
| [getRight()](#getRight--) | 오른쪽. |
| [getBottom()](#getBottom--) | 아래쪽. |
| [getChart()](#getChart--) | 차트. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | 위치 계산 방법을 정의합니다: true – 자동으로 계산; X, Y, Width, Height 속성으로 정의됩니다. |
| [getLayoutTargetType()](#getLayoutTargetType--) | 플롯 영역 레이아웃이 수동으로 정의된 경우 이 속성은 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 레이아웃할지 지정합니다. |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | 플롯 영역 레이아웃이 수동으로 정의된 경우 이 속성은 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 레이아웃할지 지정합니다. |
| [getActualX()](#getActualX--) | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리 기준으로 지정합니다. |
| [getActualY()](#getActualY--) | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리 기준으로 지정합니다. |
| [getActualWidth()](#getActualWidth--) | 차트 요소의 실제 너비를 지정합니다. |
| [getActualHeight()](#getActualHeight--) | 차트 요소의 실제 높이를 지정합니다. |
| [getSlide()](#getSlide--) | FillFormat의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 상위 프레젠테이션을 반환합니다. |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

플롯 영역의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환값:**  
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

플롯 영역 경계 상자의 왼쪽 위 모서리의 x 좌표를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

플롯 영역 경계 상자의 왼쪽 위 모서리의 x 좌표를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

플롯 영역 경계 상자의 왼쪽 위 모서리의 y 좌표를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

플롯 영역 경계 상자의 왼쪽 위 모서리의 y 좌표를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

플롯 영역 경계 상자의 너비를 차트 너비의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

플롯 영역 경계 상자의 높이를 차트 높이의 비율(0~1)로 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

오른쪽. 읽기 전용 float.

**반환값:**  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

아래쪽. 읽기 전용 float.

**반환값:**  
float

### getChart() {#getChart--}
```
public final IChart getChart()
```

차트. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환값:**  
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

위치 계산 방법을 정의합니다: true – 자동으로 계산; X, Y, Width, Height 속성으로 정의됩니다. 읽기 전용 boolean.

**반환값:**  
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

플롯 영역 레이아웃이 수동으로 정의된 경우 이 속성은 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 레이아웃할지 지정합니다. 읽기/쓰기 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**반환값:**  
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

플롯 영역 레이아웃이 수동으로 정의된 경우 이 속성은 내부(축 및 축 레이블 제외) 또는 외부(축 및 축 레이블 포함) 중 어디에 레이아웃할지 지정합니다. 읽기/쓰기 [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리 기준으로 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

차트 요소의 실제 상단을 차트 왼쪽 상단 모서리 기준으로 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**  
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation)