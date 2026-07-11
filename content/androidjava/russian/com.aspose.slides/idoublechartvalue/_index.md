---
title: IDoubleChartValue
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет значение double, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
type: docs
url: /ru/com.aspose.slides/idoublechartvalue/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Представляет значение double, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Возвращает или устанавливает буквальное значение double, если DataSourceType = Charts.DataSourceType.DoubleLiterals. Чтение/запись double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Возвращает или устанавливает буквальное значение double, если DataSourceType = Charts.DataSourceType.DoubleLiterals. Чтение/запись double. |
| [toDouble()](#toDouble--) | Преобразует в double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Возвращает или устанавливает буквальное значение double, если DataSourceType = Charts.DataSourceType.DoubleLiterals. Чтение/запись double.

**Возвращаемое значение:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Возвращает или устанавливает буквальное значение double, если DataSourceType = Charts.DataSourceType.DoubleLiterals. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Преобразует в double.

**Возвращаемое значение:**
double - Значение Double.