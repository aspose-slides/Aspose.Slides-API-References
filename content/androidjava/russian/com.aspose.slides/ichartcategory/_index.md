---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет категории диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Представляет категории диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getUseCell()](#getUseCell--) | Если true, то свойство AsCell актуально. |
| [getAsCell()](#getAsCell--) | Возвращает или задает объект IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Возвращает или задает объект IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Возвращает или задает AsLiteral, если UseCell равно false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Возвращает или задает AsLiteral, если UseCell равно false. |
| [getValue()](#getValue--) | Если UseCell равно true, то это свойство представляет свойство AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Если UseCell равно true, то это свойство представляет свойство AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Управляемый контейнер значений уровней группировки категорий диаграммы. |
| [remove()](#remove--) | Удаляет категорию из диаграммы. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Если true, то свойство AsCell актуально. Другими словами, лист используется для хранения категории (в этом случае поддерживается многоуровневая категория). Если false, то свойство AsLiteral актуально. Другими словами, лист НЕ используется для хранения категории (и в этом случае не поддерживаются многоуровневые категории). Только для чтения, тип boolean.

--------------------

Для изменения значения этого свойства (для всех категорий в коллекции) установите новое значение в свойство [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Возвращаемое значение:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Возвращает или задает объект IChartDataCell. Если категория многоуровневая, используется объект IChartDataCell для уровня "0". Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Возвращает или задает объект IChartDataCell. Если категория многоуровневая, используется объект IChartDataCell для уровня "0". Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Возвращает или задает AsLiteral, если UseCell равно false. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Возвращает или задает AsLiteral, если UseCell равно false. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Если UseCell равно true, то это свойство представляет свойство AsCell.Value. Если UseCell равно false, то это свойство представляет свойство AsLiteral. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Если UseCell равно true, то это свойство представляет свойство AsCell.Value. Если UseCell равно false, то это свойство представляет свойство AsLiteral. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Управляемый контейнер значений уровней группировки категорий диаграммы. Многоуровневая категория содержит более одного уровня группировки. Индексация уровней группировки начинается с нуля. Только для чтения [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Возвращаемое значение:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Удаляет категорию из диаграммы.