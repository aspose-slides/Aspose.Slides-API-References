---
title: DoubleChartValue
second_title: "Aspose.Slides для Android через справочник Java API"
description: "Представляет значение double, которое может храниться в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанных с диаграммой; 2) как литеральное значение."
type: docs
url: /ru/com.aspose.slides/doublechartvalue/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Все реализованные интерфейсы:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Представляет значение double, которое может храниться в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанными с диаграммой; 2) как литеральное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Возвращает или задает ячейку данных диаграммы. Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Возвращает или задает ячейку данных диаграммы. Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Возвращает или задает значение как литеральный double. Чтение/запись double.

**Возвращаемое значение:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Возвращает или задает значение как литеральный double. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

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

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Преобразует в double.

**Возвращаемое значение:**
double — Возвращает LiteralDouble, если DataSourceType равно DoubleLiterals. Если DataSourceType равно Worksheet, возвращает успешно преобразованное в double значение ячейки, иначе возвращает NaN.