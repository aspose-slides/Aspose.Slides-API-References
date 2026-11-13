---
title: DataLabel
second_title: Aspose.Slides for Java API 레퍼런스
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/datalabel/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject  
```
public class DataLabel implements IDataLabel, IDOMObject
```

시리즈 레이블을 나타냅니다.

## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel 클래스를 새 인스턴스로 생성합니다. |

## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 보이지 않음을 의미하며(따라서 모든 Show*-플래그(ShowValue 등)가 false입니다). |
| [hide()](#hide--) | 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 매개변수 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 서식이 지정된 풍부한 텍스트를 포함할 수 있습니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getX()](#getX--) | 차트 너비에 대한 비율로 제목의 x 좌표를 반환하거나 설정합니다. |
| [setX(float value)](#setX-float-) | 차트 너비에 대한 비율로 제목의 x 좌표를 반환하거나 설정합니다. |
| [getY()](#getY--) | 차트 높이에 대한 비율로 제목의 y 좌표를 반환하거나 설정합니다. |
| [setY(float value)](#setY-float-) | 차트 높이에 대한 비율로 제목의 y 좌표를 반환하거나 설정합니다. |
| [getWidth()](#getWidth--) | 차트 너비에 대한 비율로 제목의 너비를 반환하거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 차트 너비에 대한 비율로 제목의 너비를 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 차트 높이에 대한 비율로 제목의 높이를 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 차트 높이에 대한 비율로 제목의 높이를 반환하거나 설정합니다. |
| [getRight()](#getRight--) | 오른쪽. |
| [getBottom()](#getBottom--) | 아래쪽. |
| [getDataLabelFormat()](#getDataLabelFormat--) | 데이터 레이블 형식을 반환합니다. |
| [getValueFromCell()](#getValueFromCell--) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [getLabelShapeType()](#getLabelShapeType--) | 데이터 레이블의 도형 유형을 가져오거나 설정합니다. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 데이터 레이블의 도형 유형을 가져오거나 설정합니다. |
| [getActualX()](#getActualX--) | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualY()](#getActualY--) | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualWidth()](#getActualWidth--) | 차트 요소의 실제 너비를 지정합니다. |
| [getActualHeight()](#getActualHeight--) | 차트 요소의 실제 높이를 지정합니다. |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel 클래스를 새 인스턴스로 생성합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 부모 ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

부모 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**Returns:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False는 데이터 레이블이 보이지 않음을 의미하며(따라서 모든 Show*-플래그(ShowValue 등)가 false입니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 보이는 경우 Hide() 메서드로 숨길 수 있습니다. 그러나 데이터 레이블이 보이지 않을 경우(IsVisible가 false) Show*-플래그(ShowValue 등)를 true 상태로 설정하여 표시할 수 있습니다.

**Returns:**  
boolean

### hide() {#hide--}
```
public final void hide()
```

모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이 후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 보이지 않을 경우(IsVisible가 false) Show*-플래그(ShowValue 등)를 true 상태로 설정하여 표시할 수 있습니다.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다.

**Returns:**  
java.lang.String - java.lang.String 객체.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding을 매개변수 "text"의 텍스트로 초기화합니다. 이미 초기화된 경우 단순히 텍스트를 변경합니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrameForOverriding의 텍스트. |

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

서식이 지정된 풍부한 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 자동 생성된 데이터 레이블 텍스트를 이 서식 있는 텍스트 값이 대체합니다. 자동 생성 텍스트는 ShowSeriesName, ShowValue 등 속성에 의해 관리되며 TextFormatManager.TextFormat 속성으로 서식이 지정됩니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

차트 너비에 대한 비율로 제목의 x 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**Returns:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

차트 너비에 대한 비율로 제목의 x 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

차트 높이에 대한 비율로 제목의 y 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**Returns:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

차트 높이에 대한 비율로 제목의 y 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

차트 너비에 대한 비율로 제목의 너비를 반환하거나 설정합니다. 읽기/쓰기 float.

**Returns:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

차트 너비에 대한 비율로 제목의 너비를 반환하거나 설정합니다. 읽기/쓰기 float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

차트 높이에 대한 비율로 제목의 높이를 반환하거나 설정합니다. 읽기/쓰기 float.

**Returns:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

차트 높이에 대한 비율로 제목의 높이를 반환하거나 설정합니다. 읽기/쓰기 float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

오른쪽. 읽기 전용 float.

**Returns:**  
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

아래쪽. 읽기 전용 float.

**Returns:**  
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

데이터 레이블 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우 적용됩니다.

**Returns:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우 적용됩니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

데이터 레이블의 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 데이터 레이블의 도형 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**  
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

데이터 레이블의 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 데이터 레이블의 도형 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 전용 float.

**Returns:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 전용 float.

**Returns:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 전용 float.

**Returns:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 전용 float.

**Returns:**  
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
[IPresentation](../../com.aspose.slides/ipresentation)