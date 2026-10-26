---
title: BulletFormat
second_title: Aspose.Slides for Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /com.aspose.slides/bulletformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Represents paragraph bullet formatting properties.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns or sets the bullet type of a paragraph with no inheritance. |
| [setType(byte value)](#setType-byte-) | Returns or sets the bullet type of a paragraph with no inheritance. |
| [getChar()](#getChar--) | Returns or sets the bullet char of a paragraph with no inheritance. |
| [setChar(char value)](#setChar-char-) | Returns or sets the bullet char of a paragraph with no inheritance. |
| [getFont()](#getFont--) | Returns or sets the bullet font of a paragraph with no inheritance. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Returns or sets the bullet font of a paragraph with no inheritance. |
| [getHeight()](#getHeight--) | Returns or sets the bullet height of a paragraph with no inheritance. |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the bullet height of a paragraph with no inheritance. |
| [getColor()](#getColor--) | Returns the color format of a bullet of a paragraph with no inheritance. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returns or sets the style of a numbered bullet with no inheritance. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returns or sets the style of a numbered bullet with no inheritance. |
| [isBulletHardColor()](#isBulletHardColor--) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [isBulletHardFont()](#isBulletHardFont--) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [getPicture()](#getPicture--) | Returns the picture used as a bullet in a paragraph with no inheritance. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). |
| [getEffective()](#getEffective--) | Gets effective bullet formatting data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Returns or sets the bullet type of a paragraph with no inheritance. Read/write [BulletType](../../com.aspose.slides/bullettype).

**Returns:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Returns or sets the bullet type of a paragraph with no inheritance. Read/write [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Returns or sets the bullet char of a paragraph with no inheritance. Read/write  char .

**Returns:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Returns or sets the bullet char of a paragraph with no inheritance. Read/write  char .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Returns or sets the bullet font of a paragraph with no inheritance. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Returns or sets the bullet font of a paragraph with no inheritance. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write  float .

--------------------

A negative height value means that the height is given in points and a positive value means the height is a percentage of the surrounding text.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write  float .

--------------------

A negative height value means that the height is given in points and a positive value means the height is a percentage of the surrounding text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returns the color format of a bullet of a paragraph with no inheritance. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write  short .

**Returns:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write  short .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Returns or sets the style of a numbered bullet with no inheritance. Read/write [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Returns:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Returns or sets the style of a numbered bullet with no inheritance. Read/write [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Determines whether the bullet has own color or inherits it from the first portion in the paragraph. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Determines whether the bullet has own color or inherits it from the first portion in the paragraph. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Determines whether the bullet has own font or inherits it from the first portion in the paragraph. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Determines whether the bullet has own font or inherits it from the first portion in the paragraph. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Returns the picture used as a bullet in a paragraph with no inheritance. Read-only [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returns:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Gets effective bullet formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
