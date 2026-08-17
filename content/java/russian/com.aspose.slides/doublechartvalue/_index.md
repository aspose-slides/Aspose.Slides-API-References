---
title: DoubleChartValue
second_title: Aspose.Slides для Java – справка API
description: Представляет значение double, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
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

Представляет значение double, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.
## Методы

| Метод | Описание |
| --- | --- |
| [getAsCell()](#getAsCell--) | Возвращает или задаёт ячейку данных диаграммы. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Возвращает или задаёт ячейку данных диаграммы. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Возвращает или задаёт значение как буквальный double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Возвращает или задаёт значение как буквальный double. |
| [getData()](#getData--) | Возвращает или задаёт объект Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Возвращает или задаёт объект Data. |
| [toDouble()](#toDouble--) | Преобразует к double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Возвращает или задаёт ячейку данных диаграммы. Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Возвращает или задаёт ячейку данных диаграммы. Чтение/запись [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Возвращает или задаёт значение как буквальный double. Чтение/запись double.

**Возвращаемое значение:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Возвращает или задаёт значение как буквальный double. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

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

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Преобразует к double.

**Возвращаемое значение:**
double - Возвращает LiteralDouble, если DataSourceType равно DoubleLiterals. Если DataSourceType равно Worksheet, возвращает успешно преобразованное в double значение ячейки, в противном случае возвращает NaN.