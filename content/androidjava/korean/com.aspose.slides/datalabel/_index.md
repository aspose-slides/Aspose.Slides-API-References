---
title: DataLabel
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/datalabel/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

시리즈 레이블을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | DataLabel 클래스의 새 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 보이지 않음을 의미합니다(따라서 모든 Show\*-플래그(ShowValue 등)가 false입니다). |
| [hide()](#hide--) | 모든 Show\*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값에 따라 실제 레이블 텍스트를 반환합니다. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 파라미터 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 리치 형식 텍스트를 포함할 수 있습니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getX()](#getX--) | 차트 너비의 비율로 제목의 x 좌표를 반환하거나 설정합니다. |
| [setX(float value)](#setX-float-) | 차트 너비의 비율로 제목의 x 좌표를 반환하거나 설정합니다. |
| [getY()](#getY--) | 차트 높이의 비율로 제목의 y 좌표를 반환하거나 설정합니다. |
| [setY(float value)](#setY-float-) | 차트 높이의 비율로 제목의 y 좌표를 반환하거나 설정합니다. |
| [getWidth()](#getWidth--) | 차트 너비의 비율로 제목의 너비를 반환하거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 차트 너비의 비율로 제목의 너비를 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 차트 높이의 비율로 제목의 높이를 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 차트 높이의 비율로 제목의 높이를 반환하거나 설정합니다. |
| [getRight()](#getRight--) | 오른쪽. |
| [getBottom()](#getBottom--) | 아래쪽. |
| [getDataLabelFormat()](#getDataLabelFormat--) | 데이터 레이블 형식을 반환합니다. |
| [getValueFromCell()](#getValueFromCell--) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [getActualX()](#getActualX--) | 차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualY()](#getActualY--) | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualWidth()](#getActualWidth--) | 차트 요소의 실제 너비를 지정합니다. |
| [getActualHeight()](#getActualHeight--) | 차트 요소의 실제 높이를 지정합니다. |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

DataLabel 클래스의 새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 부모 ChartDataPoint. |
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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False는 데이터 레이블이 보이지 않음을 의미합니다(따라서 모든 Show*-플래그(ShowValue 등)가 false입니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 보이는 경우 Hide() 메서드를 사용하여 숨길 수 있습니다. 그러나 데이터 레이블이 보이지 않는 경우(IsVisible가 false) Show*-플래그(ShowValue 등)를 true 상태로 설정하여 보이게 만들 수 있습니다.

**반환값:**
boolean
### hide() {#hide--}
```
public final void hide()
```

모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 보이지 않는 경우(IsVisible가 false) Show*-플래그(ShowValue 등)를 true 상태로 설정하여 보이게 만들 수 있습니다.
### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값에 따라 실제 레이블 텍스트를 반환합니다.

**반환값:**
java.lang.String - java.lang.String 객체.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

파라미터 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 단순히 텍스트를 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrameForOverriding에 대한 텍스트. |

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

리치 형식 텍스트를 포함할 수 있습니다. 이 속성이 null이 아닌 경우 이 형식된 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 재정의합니다. 데이터 레이블의 자동 생성 텍스트는 ShowSeriesName, ShowValue 등 속성에 의해 관리되고 TextFormatManager.TextFormat 속성으로 형식이 지정된 텍스트를 의미합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환값:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

차트 너비의 비율로 제목의 x 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

차트 너비의 비율로 제목의 x 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

차트 높이의 비율로 제목의 y 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

차트 높이의 비율로 제목의 y 좌표를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

차트 너비의 비율로 제목의 너비를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

차트 너비의 비율로 제목의 너비를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

차트 높이의 비율로 제목의 높이를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환값:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

차트 높이의 비율로 제목의 높이를 반환하거나 설정합니다. 읽기/쓰기 float.

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
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

데이터 레이블 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환값:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다.

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 float.

**반환값:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 float.

**반환값:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 float.

**반환값:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. 읽기 float.

**반환값:**
float
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