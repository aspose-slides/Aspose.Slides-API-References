---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides для Android через справку Java API
description: Представляет строковое или двойное значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках листа рабочей книги, связанном с диаграммой; 2) как буквальное значение.
type: docs
url: /ru/com.aspose.slides/istringordoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Представляет строковое или двойное значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках листа книги, связанном с диаграммой; 2) как буквальное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Возвращает или задаёт буквальную строку, если свойство DataSourceType имеет значение DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Возвращает или задаёт буквальную строку, если свойство DataSourceType имеет значение DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Возвращает или задаёт буквальное двойное значение, если свойство DataSourceType имеет значение DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Возвращает или задаёт буквальное двойное значение, если свойство DataSourceType имеет значение DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Преобразует значение в double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Возвращает или задаёт буквальную строку, если свойство DataSourceType имеет значение DataSourceType.StringLiterals. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Возвращает или задаёт буквальную строку, если свойство DataSourceType имеет значение DataSourceType.StringLiterals. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Возвращает или задаёт буквальное двойное значение, если свойство DataSourceType имеет значение DataSourceType.DoubleLiterals. Чтение/запись double.

**Возвращаемое значение:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Возвращает или задаёт буквальное двойное значение, если свойство DataSourceType имеет значение DataSourceType.DoubleLiterals. Чтение/запись double.

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
double - Double value double