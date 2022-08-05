---
title: Column
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a column in a table.
type: docs
weight: 120
url: /java/com.aspose.slides/column/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Represents a column in a table.
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Returns or sets the width of a column. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a column. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all column cells' portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all column cells' paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all column cells' text frames. |
| [getColumnFormat()](#getColumnFormat--) | Returns the ColumnFormat object that contains formatting properties for this column. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Returns or sets the width of a column. Read/write double.

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Returns or sets the width of a column. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Sets defined portion format properties to all column cells' portions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Sets defined paragraph format properties to all column cells' paragraphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Sets defined text frame format properties to all column cells' text frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Returns the ColumnFormat object that contains formatting properties for this column. Read-only [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returns:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
