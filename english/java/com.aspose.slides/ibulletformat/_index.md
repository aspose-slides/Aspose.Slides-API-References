---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description:  Represents paragraph bullet formatting properties.
type: docs
weight: 670
url: /java/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
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
| [getPicture()](#getPicture--) | Returns the picture used as a bullet in a paragraph with no inheritance. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Returns or sets the style of a numbered bullet with no inheritance. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Returns or sets the style of a numbered bullet with no inheritance. |
| [isBulletHardColor()](#isBulletHardColor--) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. |
| [isBulletHardFont()](#isBulletHardFont--) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). |
| [getEffective()](#getEffective--) | Gets effective bullet formatting data with the inheritance applied. |
### getType() {#getType--}
```
public abstract byte getType()
```


Returns or sets the bullet type of a paragraph with no inheritance. Read/write [BulletType](../../com.aspose.slides/bullettype).

**Returns:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Returns or sets the bullet type of a paragraph with no inheritance. Read/write [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Returns or sets the bullet char of a paragraph with no inheritance. Read/write char.

**Returns:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Returns or sets the bullet char of a paragraph with no inheritance. Read/write char.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Returns or sets the bullet font of a paragraph with no inheritance. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Returns or sets the bullet font of a paragraph with no inheritance. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Returns the color format of a bullet of a paragraph with no inheritance. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Returns the picture used as a bullet in a paragraph with no inheritance. Read-only [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returns:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short.

**Returns:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Returns or sets the style of a numbered bullet with no inheritance. Read/write [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle/\#setNumberedBulletStyle(byte)).

**Returns:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Returns or sets the style of a numbered bullet with no inheritance. Read/write [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle/\#setNumberedBulletStyle(byte)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Determines whether the bullet has own color or inherits it from the first portion in the paragraph. **NullableBool\#True** if bullet has own color and **NullableBool\#False** if bullet inherits color from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Determines whether the bullet has own color or inherits it from the first portion in the paragraph. **NullableBool\#True** if bullet has own color and **NullableBool\#False** if bullet inherits color from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Determines whether the bullet has own font or inherits it from the first portion in the paragraph. **NullableBool\#True** if bullet has own font and **NullableBool\#False** if bullet inherits font from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Determines whether the bullet has own font or inherits it from the first portion in the paragraph. **NullableBool\#True** if bullet has own font and **NullableBool\#False** if bullet inherits font from the first portion in the paragraph. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../com.aspose.slides/ibulletformateffectivedata).
