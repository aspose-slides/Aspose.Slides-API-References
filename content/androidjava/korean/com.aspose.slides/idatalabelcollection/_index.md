---
title: IDataLabelCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Represents a series labels.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 데이터 포인트에 대한 데이터 레이블을 가져옵니다. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 컬렉션에 있는 모든 데이터 레이블의 기본 형식을 반환합니다. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 데이터 레이블 리더 라인 형식을 나타냅니다. |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false입니다). |
| [hide()](#hide--) | DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 컬렉션에 있는 보이는 데이터 레이블의 수를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. |
| [getParentSeries()](#getParentSeries--) | 부모 차트 시리즈를 반환합니다. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

지정된 인덱스의 데이터 포인트에 대한 데이터 레이블을 가져옵니다.

--------------------

데이터 레이블에 접근하는 대체 방법은 다음과 같습니다: - getSeries().getDataPoints().get_Item(i).getLabel() - 레이블 속성을 관리합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

컬렉션에 있는 모든 데이터 레이블의 기본 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)가 false입니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 기본적으로 보이는 경우 Hide() 메서드를 사용하여 기본적으로 숨길 수 있습니다. 그러나 데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue 등)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다. 이 후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 기본적으로 보이지 않는 경우(IsVisible가 false) DefaultDataLabelFormat 속성의 Show*-플래그(ShowValue 등)를 true 상태로 설정하여 데이터 레이블을 "기본적으로 보이게" 만들 수 있습니다.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

컬렉션에 있는 보이는 데이터 레이블의 수를 가져옵니다. 읽기 전용 int.

**Returns:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다. 읽기 전용 int.

**Returns:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

부모 차트 시리즈를 반환합니다. 읽기 전용 [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 찾을 DataLabel. |

**Returns:**
int - DataLabel의 인덱스 또는 DataLabel이 이 컬렉션에 속하지 않으면 -1.