---
title: IRow
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет строку в таблице.
type: docs
url: /ru/com.aspose.slides/irow/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Представляет строку в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeight()](#getHeight--) | Возвращает высоту строки. |
| [getMinimalHeight()](#getMinimalHeight--) | Возвращает или устанавливает минимально возможную высоту строки. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Возвращает или устанавливает минимально возможную высоту строки. |
| [getRowFormat()](#getRowFormat--) | Возвращает объект RowFormat, содержащий свойства форматирования для этой строки. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Возвращает высоту строки. Только для чтения double.

**Возвращаемое значение:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Возвращает или устанавливает минимально возможную высоту строки. Чтение/запись double.

**Возвращаемое значение:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Возвращает или устанавливает минимально возможную высоту строки. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Возвращает объект RowFormat, содержащий свойства форматирования для этой строки. Только для чтения [IRowFormat](../../com.aspose.slides/irowformat).

**Возвращаемое значение:**
[IRowFormat](../../com.aspose.slides/irowformat)