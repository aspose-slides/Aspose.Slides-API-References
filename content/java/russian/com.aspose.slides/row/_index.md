---
title: Row
second_title: Aspose.Slides для Java: справочник API
description: Представляет строку в таблице.
type: docs
url: /ru/com.aspose.slides/row/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Все реализованные интерфейсы:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Представляет строку в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeight()](#getHeight--) | Возвращает высоту строки. |
| [getMinimalHeight()](#getMinimalHeight--) | Возвращает или задает минимально возможную высоту строки. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Возвращает или задает минимально возможную высоту строки. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Устанавливает определённые свойства формата части для всех частей ячеек строки. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Устанавливает определённые свойства формата абзаца для всех абзацев ячеек строки. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Устанавливает определённые свойства формата текстового фрейма для всех текстовых фреймов ячеек строки. |
| [getRowFormat()](#getRowFormat--) | Возвращает объект RowFormat, содержащий свойства форматирования для этой строки. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Возвращает высоту строки. Только для чтения double.

**Возвращает:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Возвращает или задает минимально возможную высоту строки. Чтение/запись double.

**Возвращает:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


Возвращает или задает минимально возможную высоту строки. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Устанавливает определённые свойства формата части для всех частей ячеек строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Объект IPortionFormat с установленными необходимыми свойствами. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Устанавливает определённые свойства формата абзаца для всех абзацев ячеек строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Объект IParagraphFormat с установленными необходимыми свойствами. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Устанавливает определённые свойства формата текстового фрейма для всех текстовых фреймов ячеек строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Объект ITextFrameFormat с установленными необходимыми свойствами. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Возвращает объект RowFormat, содержащий свойства форматирования для этой строки. Только для чтения [IRowFormat](../../com.aspose.slides/irowformat).

**Возвращает:**
[IRowFormat](../../com.aspose.slides/irowformat)