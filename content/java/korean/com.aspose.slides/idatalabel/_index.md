---
title: IDataLabel
second_title: Aspose.Slides for Java API 참조
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

시리즈 레이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 표시되지 않음을 의미합니다(따라서 모든 Show*-플래그(ShowValue, ...)가 false입니다). |
| [hide()](#hide--) | 모든 Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. |
| [getDataLabelFormat()](#getDataLabelFormat--) | 데이터 레이블의 형식을 반환합니다. |
| [getValueFromCell()](#getValueFromCell--) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 설정이나 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다. |
| [getLabelShapeType()](#getLabelShapeType--) | 데이터 레이블의 도형 유형을 가져오거나 설정합니다. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 데이터 레이블의 도형 유형을 가져오거나 설정합니다. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False는 데이터 레이블이 표시되지 않음을 의미합니다(따라서 모든 Show*-플래그(ShowValue, ...)가 false입니다). 읽기 전용 부울.

--------------------

데이터 레이블이 표시되어 있으면 Hide() 메서드로 숨길 수 있습니다. 그러나 데이터 레이블이 표시되지 않으면(IsVisible가 false) Show*-플래그(ShowValue, ...)를 true 상태로 설정하여 표시할 수 있습니다.

**반환:**  
boolean
### hide() {#hide--}
```
public abstract void hide()
```

모든 Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 표시되지 않으면(IsVisible가 false) Show*-플래그(ShowValue, ...)를 true 상태로 설정하여 표시할 수 있습니다.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

데이터 레이블의 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우 적용됩니다.

**반환:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우 적용됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat 설정이나 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다.

**반환:**  
java.lang.String - 실제 레이블 텍스트 문자열
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

데이터 레이블의 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 데이터 레이블의 모양 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

데이터 레이블의 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 데이터 레이블의 모양 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |