---
title: DataLabelCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

시리즈 레이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false가 됩니다). |
| [hide()](#hide--) | DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 컬렉션에서 보이는 데이터 레이블의 수를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 기본 데이터 레이블 형식을 가져옵니다. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 데이터 레이블 리더 라인 형식을 나타냅니다. |
| [getParentSeries()](#getParentSeries--) | 부모 시리즈를 가져옵니다. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | 데이터 레이블의 기본 도형 유형을 가져오거나 설정합니다. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | 데이터 레이블의 기본 도형 유형을 가져오거나 설정합니다. |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

부모 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

컬렉션을 반복하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 컬렉션을 반복하는 데 사용할 수 있는 IGenericEnumerator입니다.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

전체 컬렉션에 대한 java 반복자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 전체 컬렉션에 대한 java.util.Iterator입니다.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false가 됩니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 기본적으로 보이는 경우 Hide() 메서드를 사용하여 기본적으로 숨길 수 있습니다. 그러나 데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

**반환:**
boolean

### hide() {#hide--}
```
public final void hide()
```

DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. 이후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

컬렉션에서 보이는 데이터 레이블의 수를 가져옵니다. 읽기 전용 int.

**반환:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. 읽기 전용 int.

**반환:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

기본 데이터 레이블 형식을 가져옵니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

데이터 레이블 리더 라인 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

부모 시리즈를 가져옵니다. 읽기 전용 [IChartSeries](../../com.aspose.slides/ichartseries).

**반환:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 찾을 DataLabel. |

**반환:**
int - DataLabel의 인덱스 또는 컬렉션에 속하지 않는 경우 -1.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다.

--------------------

데이터 레이블에 접근하는 대안 방법은 다음과 같습니다: - series.getDataPoints().get_Item(i).getLabel() - 레이블 속성을 관리합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

데이터 레이블의 기본 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 시리즈의 모든 데이터 레이블의 모양 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

이 속성을 설정하면 컬렉션에 있는 모든 데이터 레이블의 IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) 속성도 동일한 값으로 설정됩니다.

**반환:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

데이터 레이블의 기본 도형 유형을 가져오거나 설정합니다. 도형이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 첫 번째 시리즈의 모든 데이터 레이블의 모양 유형을 Ellipse로 설정합니다.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

이 속성을 설정하면 컬렉션에 있는 모든 데이터 레이블의 IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) 속성도 동일한 값으로 설정됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)