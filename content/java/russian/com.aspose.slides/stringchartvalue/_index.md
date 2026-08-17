---
title: StringChartValue
second_title: Справочник API Aspose.Slides для Java
description: Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
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

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsCells()](#getAsCells--) | Назначение нулевого значения не разрешено. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Назначение нулевого значения не разрешено. |
| [getAsLiteralString()](#getAsLiteralString--) | Возвращает или задает значение как буквальную строку. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Возвращает или задает значение как буквальную строку. |
| [getData()](#getData--) | Возвращает или задает объект Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Возвращает или задает объект Data. |
| [toString()](#toString--) | Возвращает данные строкового значения. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Устанавливает значение из указанной ячейки. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Если свойство DataSourceType равно DataSourceType.Worksheet, то этот метод возвращает адрес ячеек в рабочей книге, которые представляют строковые данные. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Назначение нулевого значения не разрешено. Возвращаемое значение всегда не равно null. Чтение/запись [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Возвращаемое значение:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Назначение нулевого значения не разрешено. Возвращаемое значение всегда не равно null. Чтение/запись [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Возвращает или задает значение как буквальную строку. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Возвращает или задает значение как буквальную строку. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Возвращает или задает объект Data. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Возвращает или задает объект Data. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Возвращает данные строкового значения. Возвращает null, если DataSourceType равно false и строковое значение не было назначено.

**Возвращаемое значение:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Устанавливает значение из указанной ячейки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ячейка. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Если свойство DataSourceType равно DataSourceType.Worksheet, то этот метод возвращает адрес ячеек в рабочей книге, которые представляют строковые данные. В противном случае возвращает пустую строку.

**Возвращаемое значение:**
java.lang.String