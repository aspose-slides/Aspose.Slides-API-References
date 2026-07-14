---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /ko/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

차트 카테고리를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getUseCell()](#getUseCell--) | true이면 AsCell 속성이 실제입니다. |
| [getAsCell()](#getAsCell--) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell 객체를 반환하거나 설정합니다. |
| [getAsLiteral()](#getAsLiteral--) | UseCell가 false인 경우 AsLiteral을 반환하거나 설정합니다. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | UseCell가 false인 경우 AsLiteral을 반환하거나 설정합니다. |
| [getValue()](#getValue--) | UseCell가 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell가 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. |
| [getGroupingLevels()](#getGroupingLevels--) | 차트 카테고리 그룹화 레벨 값들의 관리 컨테이너입니다. |
| [remove()](#remove--) | 차트에서 카테고리를 제거합니다. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

true이면 AsCell 속성이 실제입니다. 즉, 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). false이면 AsLiteral 속성이 실제입니다. 즉, 워크시트는 카테고리를 저장하는 데 사용되지 않습니다(이 경우 다중 레벨 카테고리를 지원하지 않습니다). 읽기 전용 boolean.

--------------------

이 속성의 값을 변경하려면(컬렉션의 모든 카테고리에 대해) 새 값을 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 속성에 설정하십시오.

**반환:**  
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell 객체를 반환하거나 설정합니다. 카테고리가 다중 레벨인 경우 레벨 "0"에 대해 IChartDataCell 객체를 사용합니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**반환:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell 객체를 반환하거나 설정합니다. 카테고리가 다중 레벨인 경우 레벨 "0"에 대해 IChartDataCell 객체를 사용합니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

UseCell가 false인 경우 AsLiteral을 반환하거나 설정합니다. 읽기/쓰기 Object.

**반환:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

UseCell가 false인 경우 AsLiteral을 반환하거나 설정합니다. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

UseCell가 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell가 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 Object.

**반환:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

UseCell가 true이면 이 속성은 AsCell.Value 속성을 나타냅니다. UseCell가 false이면 이 속성은 AsLiteral 속성을 나타냅니다. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

차트 카테고리 그룹화 레벨 값들의 관리 컨테이너입니다. 다중 레벨 카테고리는 하나 이상의 그룹화 레벨을 포함합니다. 그룹화 레벨 인덱스는 0부터 시작합니다. 읽기 전용 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**반환:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

차트에서 카테고리를 제거합니다.