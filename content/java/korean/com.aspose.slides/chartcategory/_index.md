---
title: ChartCategory
second_title: Aspose.Slides for Java API 레퍼런스
description: 차트 카테고리를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartcategory/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

차트 카테고리를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | true이면 AsCell 속성이 실제입니다. |
| [getAsCell()](#getAsCell--) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral 객체를 반환하거나 설정합니다. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral 객체를 반환하거나 설정합니다. |
| [getValue()](#getValue--) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [getGroupingLevels()](#getGroupingLevels--) | 차트 카테고리 그룹화 수준 값들의 관리 컨테이너입니다. |
| [remove()](#remove--) | 차트에서 카테고리를 제거합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

If true then AsCell property is actual. In other words, worksheet is used for storing category (this case supports a multi-level category). If false then AsLiteral property is actual. In other words, worksheet is NOT used for storing category (and this case doesn't support a multi-level categories). Read-only boolean.

true이면 AsCell 속성이 실제입니다. 즉, 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). false이면 AsLiteral 속성이 실제입니다. 즉, 워크시트가 카테고리를 저장하는 데 사용되지 않습니다(이 경우 다중 레벨 카테고리를 지원하지 않습니다). 읽기 전용 boolean.

--------------------

For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property.

**반환값:**  
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell 객체를 반환하거나 설정합니다. 카테고리가 다중 레벨인 경우 레벨 "0"에 대해 IChartDataCell 객체가 사용됩니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**반환값:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell 객체를 반환하거나 설정합니다. 카테고리가 다중 레벨인 경우 레벨 "0"에 대해 IChartDataCell 객체가 사용됩니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral 객체를 반환하거나 설정합니다. 읽기/쓰기 Object.

**반환값:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral 객체를 반환하거나 설정합니다. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 Object.

**반환값:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

차트 카테고리 그룹화 수준 값들의 관리 컨테이너입니다. 다중 레벨 카테고리는 하나 이상의 그룹화 수준을 포함합니다. 그룹화 수준 인덱스는 0부터 시작합니다. 읽기 전용 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**반환값:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

차트에서 카테고리를 제거합니다.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**  
com.aspose.slides.IDOMObject