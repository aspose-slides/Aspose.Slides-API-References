---
title: StringChartValue
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграмой; 2) как литеральное значение.
type: docs
url: /ru/com.aspose.slides/stringchartvalue/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Все реализованные интерфейсы:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как литеральное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsCells()](#getAsCells--) | Присваивание нулевого значения не допускается. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Присваивание нулевого значения не допускается. |
| [getAsLiteralString()](#getAsLiteralString--) | Возвращает или задаёт значение как литеральную строку. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Возвращает или задаёт значение как литеральную строку. |
| [getData()](#getData--) | Возвращает или задаёт объект Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Возвращает или задаёт объект Data. |
| [toString()](#toString--) | Возвращает данные строкового значения. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Задаёт значение из указанной ячейки. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Если свойство DataSourceType имеет значение DataSourceType.Worksheet, этот метод возвращает адрес ячеек в рабочей книге, представляющих строковые данные. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```


Присваивание нулевого значения не допускается. Возвращаемое значение всегда не null. Чтение/запись [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Возвращаемое значение:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```


Присваивание нулевого значения не допускается. Возвращаемое значение всегда не null. Чтение/запись [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Возвращает или задаёт значение как литеральную строку. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Возвращает или задаёт значение как литеральную строку. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```


Возвращает или задаёт объект Data. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Возвращает или задаёт объект Data. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает данные строкового значения. Возвращает null, если DataSourceType имеет значение false и строковое значение не было назначено.

**Возвращаемое значение:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```


Задаёт значение из указанной ячейки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```


Если свойство DataSourceType имеет значение DataSourceType.Worksheet, этот метод возвращает адрес ячеек в рабочей книге, представляющих строковые данные. В противном случае возвращает пустую строку.

**Возвращаемое значение:**
java.lang.String