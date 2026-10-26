---
title: ChartCategory
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет категории диаграммы.
type: docs
url: /ru/com.aspose.slides/chartcategory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```


Представляет категории диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getUseCell()](#getUseCell--) | Если true, то свойство AsCell действительно. |
| [getAsCell()](#getAsCell--) | Возвращает или задаёт объект IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Возвращает или задаёт объект IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Возвращает или задаёт объект AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Возвращает или задаёт объект AsLiteral. |
| [getValue()](#getValue--) | Если UseCell true, то это свойство представляет свойство AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Если UseCell true, то это свойство представляет свойство AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Управляемый контейнер значений уровней группировки категорий диаграммы. |
| [remove()](#remove--) | Удаляет категорию из диаграммы. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Если true, то свойство AsCell действительно. Другими словами, лист используется для хранения категории (в этом случае поддерживается многоуровневая категория). Если false, то свойство AsLiteral действительно. Другими словами, лист НЕ используется для хранения категории (и в этом случае многоуровневые категории не поддерживаются). Только для чтения: логический.

--------------------

Для изменения значения этого свойства (для всех категорий в коллекции) задайте новое значение свойству ChartCategoryCollection.UseCells.

**Возвращаемое значение:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Возвращает или задаёт объект IChartDataCell. Если категория многоуровневая, используется объект IChartDataCell для уровня "0". Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Возвращает или задаёт объект IChartDataCell. Если категория многоуровневая, используется объект IChartDataCell для уровня "0". Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Возвращает или задаёт объект AsLiteral. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Возвращает или задаёт объект AsLiteral. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Если UseCell true, то это свойство представляет свойство AsCell.Value. Если UseCell false, то это свойство представляет свойство AsLiteral. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Если UseCell true, то это свойство представляет свойство AsCell.Value. Если UseCell false, то это свойство представляет свойство AsLiteral. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Управляемый контейнер значений уровней группировки категорий диаграммы. Многоуровневая категория содержит более одного уровня группировки. Индексация уровней группировки начинается с нуля. Только для чтения [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Возвращаемое значение:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Удаляет категорию из диаграммы.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject