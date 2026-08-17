---
title: IStringChartValue
second_title: Aspose.Slides для Java — справочник API
description: Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
type: docs
url: /ru/com.aspose.slides/istringchartvalue/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Возвращает или задает буквальную строку, если свойство DataSourceType равно DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Возвращает или задает буквальную строку, если свойство DataSourceType равно DataSourceType.StringLiterals. |
| [toString()](#toString--) | Возвращает строковое представление. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Задает значение из указанной ячейки. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Если свойство DataSourceType равно DataSourceType.Worksheet, этот метод возвращает адрес ячеек в рабочей книге, представляющих строковые данные. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Возвращает или задает буквальную строку, если свойство DataSourceType равно DataSourceType.StringLiterals. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Возвращает или задает буквальную строку, если свойство DataSourceType равно DataSourceType.StringLiterals. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Возвращает строковое представление.

**Возвращаемое значение:**
java.lang.String - строковое представление значения String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Задает значение из указанной ячейки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Если свойство DataSourceType равно DataSourceType.Worksheet, этот метод возвращает адрес ячеек в рабочей книге, представляющих строковые данные. В противном случае возвращает пустую строку.

**Возвращаемое значение:**
java.lang.String - строковое значение String