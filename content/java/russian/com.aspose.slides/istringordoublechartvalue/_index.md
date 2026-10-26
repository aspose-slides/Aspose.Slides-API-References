---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides для Java справка API
description: Представляет строковое или числовое значение double, которое может быть сохранено в документе презентации pptx двумя способами 1) в ячейке/ячейках рабочей книги, связанных с диаграммой 2) как литеральное значение.
type: docs
url: /ru/com.aspose.slides/istringordoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Представляет строковое или числовое значение double, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках книги, связанных с диаграммой; 2) как литеральное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Возвращает или задает строковый литерал, если свойство DataSourceType равно DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Возвращает или задает строковый литерал, если свойство DataSourceType равно DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Возвращает или задает числовой литерал double, если свойство DataSourceType равно DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Возвращает или задает числовой литерал double, если свойство DataSourceType равно DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Преобразует значение в double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Возвращает или задает строковый литерал, если свойство DataSourceType равно DataSourceType.StringLiterals. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Возвращает или задает строковый литерал, если свойство DataSourceType равно DataSourceType.StringLiterals. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Возвращает или задает числовой литерал double, если свойство DataSourceType равно DataSourceType.DoubleLiterals. Чтение/запись double.

**Возвращаемое значение:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Возвращает или задает числовой литерал double, если свойство DataSourceType равно DataSourceType.DoubleLiterals. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Преобразует значение в double.

**Возвращаемое значение:**
double - значение типа double