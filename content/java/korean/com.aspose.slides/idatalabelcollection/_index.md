---
title: IDataLabelCollection
second_title: Aspose.Slides for Java API 참조
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabelcollection/
---
**모든 구현된 인터페이스:**  
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
| [isVisible()](#isVisible--) | False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false입니다). |
| [hide()](#hide--) | DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 컬렉션에 있는 표시되는 데이터 레이블 수를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 모든 데이터 레이블 수를 가져옵니다. |
| [getParentSeries()](#getParentSeries--) | 부모 차트 시리즈를 반환합니다. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Gets the data label for the data point with the specified index.

--------------------

Alternate way to access data label is: - getSeries().getDataPoints().get_Item(i).getLabel() - 레이블 속성을 관리합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

컬렉션에 있는 모든 데이터 레이블의 기본 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환값:**
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

**반환값:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false입니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 기본적으로 표시되는 경우 Hide() 메서드를 사용하여 기본적으로 숨길 수 있습니다. 하지만 데이터 레이블이 기본적으로 표시되지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 표시"하도록 만들 수 있습니다.

**반환값:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. 이후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 기본적으로 표시되지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 표시"하도록 만들 수 있습니다.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

컬렉션에 있는 표시되는 데이터 레이블 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 모든 데이터 레이블 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

부모 차트 시리즈를 반환합니다. 읽기 전용 [IChartSeries](../../com.aspose.slides/ichartseries).

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 찾을 DataLabel. |

**반환값:**
int - DataLabel의 인덱스 또는 DataLabel이 이 컬렉션에 속하지 않을 경우 -1.