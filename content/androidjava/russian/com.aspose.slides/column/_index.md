---
title: Column
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет столбец в таблице.
type: docs
url: /ru/com.aspose.slides/column/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Все реализованные интерфейсы:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Представляет столбец в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Возвращает или задает ширину столбца. |
| [setWidth(double value)](#setWidth-double-) | Возвращает или задает ширину столбца. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Задает определённые свойства формата части для всех частей ячеек столбца. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Задает определённые свойства формата абзаца для всех абзацев ячеек столбца. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Задает определённые свойства формата текстового фрейма для всех текстовых фреймов ячеек столбца. |
| [getColumnFormat()](#getColumnFormat--) | Возвращает объект ColumnFormat, содержащий свойства форматирования для этого столбца. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Возвращает или задает ширину столбца. Чтение/запись double.

**Возвращаемое значение:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Возвращает или задает ширину столбца. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Задает определённые свойства формата части для всех частей ячеек столбца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat объект с необходимыми установленными свойствами. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Задает определённые свойства формата абзаца для всех абзацев ячеек столбца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat объект с необходимыми установленными свойствами. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


Задает определённые свойства формата текстового фрейма для всех текстовых фреймов ячеек столбца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat объект с необходимыми установленными свойствами. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Возвращает объект ColumnFormat, содержащий свойства форматирования для этого столбца. Только для чтения [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Возвращаемое значение:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)