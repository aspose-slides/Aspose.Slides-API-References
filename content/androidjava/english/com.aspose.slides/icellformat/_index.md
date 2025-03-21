---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Represents format of a table cell.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a cell fill properties object. |
| [getBorderLeft()](#getBorderLeft--) | Returns a left border line properties object. |
| [getBorderTop()](#getBorderTop--) | Returns a top border line properties object. |
| [getBorderRight()](#getBorderRight--) | Returns a right border line properties object. |
| [getBorderBottom()](#getBorderBottom--) | Returns a bottom border line properties object. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returns a top-left to bottom-right diagonal line properties object. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returns a bottom-left to top-right diagonal line properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table cell formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returns a cell fill properties object. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Returns a left border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Returns a top border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Returns a right border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Returns a bottom border line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Returns a top-left to bottom-right diagonal line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Returns a bottom-left to top-right diagonal line properties object. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Gets or sets the transparency of the fill color. Read/write  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Gets or sets the transparency of the fill color. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Gets effective table cell formatting properties with inheritance and table styles applied.

**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
