---
title: ChartCategory
second_title: Aspose.Slides for Java API 레퍼런스
description: 차트 범주를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartcategory/
---
**상속:**
java.lang.Object

**모든 구현 인터페이스:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

차트 범주를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true이면 AsCell 속성이 실제입니다. |
| [getAsCell()](#getAsCell--) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral 객체를 반환하거나 설정합니다. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral 객체를 반환하거나 설정합니다. |
| [getValue()](#getValue--) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [getGroupingLevels()](#getGroupingLevels--) | 차트 범주 그룹화 수준 값들의 관리되는 컨테이너입니다. |
| [getCachedValue()](#getCachedValue--) | 차트 범주의 캐시된 값을 가져옵니다. |
| [remove()](#remove--) | 차트에서 범주를 제거합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

true이면 AsCell 속성이 실제입니다. 다시 말해, 워크시트가 범주를 저장하는 데 사용됩니다(이 경우 다중 수준 범주를 지원합니다). false이면 AsLiteral 속성이 실제입니다. 다시 말해, 워크시트가 범주를 저장하는 데 사용되지 않으며(이 경우 다중 수준 범주를 지원하지 않습니다). 읽기 전용 부울.

--------------------

이 속성의 값을 변경하려면(컬렉션의 모든 범주에 대해) ChartCategoryCollection.UseCells 속성에 새 값을 설정하십시오.

**반환값:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell 객체를 반환하거나 설정합니다. 범주가 다중 수준인 경우 수준 "0"에 대한 IChartDataCell 객체가 사용됩니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell 객체를 반환하거나 설정합니다. 범주가 다중 수준인 경우 수준 "0"에 대한 IChartDataCell 객체가 사용됩니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral 객체를 반환하거나 설정합니다. 읽기/쓰기 객체.

**반환값:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral 객체를 반환하거나 설정합니다. 읽기/쓰기 객체.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 객체.

**반환값:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 객체.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

차트 범주 그룹화 수준 값들의 관리되는 컨테이너입니다. 다중 수준 범주는 하나 이상의 그룹화 수준을 포함합니다. 그룹화 수준 인덱스는 0부터 시작합니다. 읽기 전용 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**반환값:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

차트 범주의 캐시된 값을 가져옵니다. 읽기 전용 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // 모든 캐시된 차트 범주 값을 출력합니다.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**반환값:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```

차트에서 범주를 제거합니다.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject