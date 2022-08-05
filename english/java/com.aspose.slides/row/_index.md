---
title: Row
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a row in a table.
type: docs
weight: 467
url: /java/com.aspose.slides/row/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Represents a row in a table.
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Returns the height of a row. |
| [getMinimalHeight()](#getMinimalHeight--) | Returns or sets the minimal possible height of a row. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returns or sets the minimal possible height of a row. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all row cells' portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all row cells' paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all row cells' text frames. |
| [getRowFormat()](#getRowFormat--) | Returns the RowFormat object that contains formatting properties for this row. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Returns the height of a row. Read-only double.

**Returns:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Returns or sets the minimal possible height of a row. Read/write double.

**Returns:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


Returns or sets the minimal possible height of a row. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Sets defined portion format properties to all row cells' portions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Sets defined paragraph format properties to all row cells' paragraphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Sets defined text frame format properties to all row cells' text frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Returns the RowFormat object that contains formatting properties for this row. Read-only [IRowFormat](../../com.aspose.slides/irowformat).

**Returns:**
[IRowFormat](../../com.aspose.slides/irowformat)
