---
title: LineFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a line.
type: docs
weight: 286
url: /androidjava/com.aspose.slides/lineformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Represents format of a line.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
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
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares with specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Returns true if line format is not defined (as just created, default). Read-only  boolean .

**Returns:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Returns the fill format of a line. Read-only [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returns:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Returns the sketch format of a line. Read-only [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returns:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Returns or sets the width of a line. Read/write  double .

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Returns or sets the width of a line. Read/write  double .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Returns or sets the line dash style. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returns:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Returns or sets the line dash style. Read/write [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Returns or sets the custom dash pattern. Read/write  float[] .

**Returns:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Returns or sets the custom dash pattern. Read/write  float[] .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Returns or sets the line cap style. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returns:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Returns or sets the line cap style. Read/write [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Returns or sets the line style. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Returns:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Returns or sets the line style. Read/write [LineStyle](../../com.aspose.slides/linestyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Returns or sets the line alignment. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Returns:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Returns or sets the line alignment. Read/write [LineAlignment](../../com.aspose.slides/linealignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Returns or sets the lines join style. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returns:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Returns or sets the lines join style. Read/write [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Returns or sets the miter limit of a line. Read/write  float .

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Returns or sets the miter limit of a line. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Returns or sets the arrowhead style at the beginning of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Returns or sets the arrowhead style at the beginning of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Returns or sets the arrowhead style at the end of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Returns or sets the arrowhead style at the end of a line. Read/write [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Returns or sets the arrowhead width at the beginning of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Returns or sets the arrowhead width at the beginning of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Returns or sets the arrowhead width at the end of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Returns or sets the arrowhead width at the end of a line. Read/write [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Returns or sets the arrowhead length at the beginning of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Returns or sets the arrowhead length at the beginning of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Returns or sets the arrowhead length at the end of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Returns or sets the arrowhead length at the end of a line. Read/write [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
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
public final ILineFormatEffectiveData getEffective()
```


Gets effective line formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
