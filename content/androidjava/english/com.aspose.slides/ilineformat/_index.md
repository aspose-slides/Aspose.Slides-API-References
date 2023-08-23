---
title: ILineFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a line.
type: docs
url: /com.aspose.slides/ilineformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Represents format of a line.
## Methods

| Method | Description |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returns true if line format is not defined (as just created, default). |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns or sets the width of a line. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns or sets the line dash style. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returns or sets the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns or sets the custom dash pattern. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returns or sets the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns or sets the line cap style. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returns or sets the line cap style. |
| [getStyle()](#getStyle--) | Returns or sets the line style. |
| [setStyle(byte value)](#setStyle-byte-) | Returns or sets the line style. |
| [getAlignment()](#getAlignment--) | Returns or sets the line alignment. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returns or sets the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns or sets the lines join style. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returns or sets the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns or sets the miter limit of a line. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returns or sets the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns or sets the arrowhead style at the beginning of a line. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returns or sets the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns or sets the arrowhead style at the end of a line. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returns or sets the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns or sets the arrowhead width at the beginning of a line. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returns or sets the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns or sets the arrowhead width at the end of a line. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returns or sets the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns or sets the arrowhead length at the beginning of a line. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returns or sets the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns or sets the arrowhead length at the end of a line. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returns or sets the arrowhead length at the end of a line. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Determines whether the two LineFormat instances are equal. |
| [getEffective()](#getEffective--) | Gets effective line formatting data with the inheritance applied. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```


Returns true if line format is not defined (as just created, default). Read-only boolean.

**Returns:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```


Returns the fill format of a line. Read-only [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returns:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```


Returns the sketch format of a line. Read-only [ISketchFormat](../../com.aspose.slides/isketchformat).

**Returns:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returns or sets the width of a line. Read/write double.

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Returns or sets the width of a line. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Returns or sets the line dash style. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returns:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```


Returns or sets the line dash style. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Returns or sets the custom dash pattern. Read/write float[].

**Returns:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```


Returns or sets the custom dash pattern. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Returns or sets the line cap style. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returns:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```


Returns or sets the line cap style. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Returns or sets the line style. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Returns:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```


Returns or sets the line style. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Returns or sets the line alignment. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Returns:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```


Returns or sets the line alignment. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Returns or sets the lines join style. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returns:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```


Returns or sets the lines join style. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Returns or sets the miter limit of a line. Read/write float.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```


Returns or sets the miter limit of a line. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Returns or sets the arrowhead style at the beginning of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```


Returns or sets the arrowhead style at the beginning of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Returns or sets the arrowhead style at the end of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```


Returns or sets the arrowhead style at the end of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Returns or sets the arrowhead width at the beginning of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```


Returns or sets the arrowhead width at the beginning of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Returns or sets the arrowhead width at the end of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```


Returns or sets the arrowhead width at the end of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Returns or sets the arrowhead length at the beginning of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```


Returns or sets the arrowhead length at the beginning of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Returns or sets the arrowhead length at the end of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```


Returns or sets the arrowhead length at the end of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```


Determines whether the two LineFormat instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | The LineFormat to compare with the current LineFormat. |

**Returns:**
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.
### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```


Gets effective line formatting data with the inheritance applied.

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
