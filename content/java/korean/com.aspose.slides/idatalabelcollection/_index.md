---
title: IDataLabelCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabelcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

시리즈 레이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 컬렉션에 있는 모든 데이터 레이블의 기본 형식을 반환합니다. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 데이터 레이블 리더 라인 형식을 나타냅니다. |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show\*-플래그(ShowValue 등)가 false입니다). |
| [hide()](#hide--) | DefaultDataLabelFormat 속성의 모든 Show\*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 컬렉션에 있는 보이는 데이터 레이블의 수를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. |
| [getParentSeries()](#getParentSeries--) | 부모 차트 시리즈를 반환합니다. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 컬렉션에 있는 지정된 DataLabel의 인덱스를 반환합니다. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | 데이터 레이블에 대한 기본 모양 유형을 가져오거나 설정합니다. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | 데이터 레이블에 대한 기본 모양 유형을 가져오거나 설정합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다.

--------------------

대체 방법으로 데이터 레이블에 접근하는 방법은: - getSeries().getDataPoints().get_Item(i).getLabel() - 레이블 속성을 관리합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**  
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

컬렉션에 있는 모든 데이터 레이블의 기본 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show\*-플래그(ShowValue 등)가 false입니다). 읽기 전용  boolean .

--------------------

데이터 레이블이 기본적으로 보이는 경우 Hide() 메서드를 사용하여 기본적으로 숨길 수 있습니다. 그러나 데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show\*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

**반환:**  
boolean
### hide() {#hide--}
```
public abstract void hide()
```

DefaultDataLabelFormat 속성의 모든 Show\*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. 이 후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show\*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

컬렉션에 있는 보이는 데이터 레이블의 수를 가져옵니다. 읽기 전용  int .

**반환:**  
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. 읽기 전용  int .

**반환:**  
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

부모 차트 시리즈를 반환합니다. 읽기 전용 [IChartSeries](../../com.aspose.slides/ichartseries).

**반환:**  
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

컬렉션에 있는 지정된 DataLabel의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 찾을 DataLabel. |

**반환:**  
int - DataLabel의 인덱스 또는 컬렉션에 속하지 않은 경우 -1.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

데이터 레이블에 대한 기본 모양 유형을 가져오거나 설정합니다. 모양이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

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
public abstract void setDefaultLabelShapeType(int value)
```

데이터 레이블에 대한 기본 모양 유형을 가져오거나 설정합니다. 모양이 정의되지 않은 경우 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)를 반환합니다.

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