---
title: BulletFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/bulletformat/
---

## BulletFormat class

 Represents paragraph bullet formatting properties.
 
### applyDefaultParagraphIndentsShifts {#applyDefaultParagraphIndentsShifts}

| Name | Description |
| --- | --- |
| applyDefaultParagraphIndentsShifts () | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Calling this method doesn't matter and throw InvalidOperationException in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception); or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |


---


### getChar {#getChar}

| Name | Description |
| --- | --- |
| getChar () | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |

 **Returns:**
char


---


### getColor {#getColor}

| Name | Description |
| --- | --- |
| getColor () | Returns the color format of a bullet of a paragraph with no inheritance. Read-only IColorFormat. |

 **Returns:**
[ColorFormat](../colorformat)


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective bullet formatting data with the inheritance applied. |

 **Returns:**
BulletFormatEffectiveData


---


### getFont {#getFont}

| Name | Description |
| --- | --- |
| getFont () | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. A negative height value means that the height is given in points and a positive value means the height is a percentage of the surrounding text. |

 **Returns:**
float


---


### getNumberedBulletStartWith {#getNumberedBulletStartWith}

| Name | Description |
| --- | --- |
| getNumberedBulletStartWith () | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |

 **Returns:**
short


---


### getNumberedBulletStyle {#getNumberedBulletStyle}

| Name | Description |
| --- | --- |
| getNumberedBulletStyle () | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |

 **Returns:**
byte


---


### getPicture {#getPicture}

| Name | Description |
| --- | --- |
| getPicture () | Returns the picture used as a bullet in a paragraph with no inheritance. Read-only ISlidesPicture. |

 **Returns:**
[Picture](../picture)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |

 **Returns:**
byte


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### isBulletHardColor {#isBulletHardColor}

| Name | Description |
| --- | --- |
| isBulletHardColor () | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |

 **Returns:**
byte


---


### isBulletHardFont {#isBulletHardFont}

| Name | Description |
| --- | --- |
| isBulletHardFont () | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |

 **Returns:**
byte


---


### setBulletHardColor {#setBulletHardColor}

| Name | Description |
| --- | --- |
| setBulletHardColor (byte) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |

 **Returns:**
void


---


### setBulletHardFont {#setBulletHardFont}

| Name | Description |
| --- | --- |
| setBulletHardFont (byte) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |

 **Returns:**
void


---


### setChar {#setChar}

| Name | Description |
| --- | --- |
| setChar (char) | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |

 **Returns:**
void


---


### setFont {#setFont}

| Name | Description |
| --- | --- |
| setFont ([FontData](../fontdata)) | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |

 **Returns:**
void


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. A negative height value means that the height is given in points and a positive value means the height is a percentage of the surrounding text. |

 **Returns:**
void


---


### setNumberedBulletStartWith {#setNumberedBulletStartWith}

| Name | Description |
| --- | --- |
| setNumberedBulletStartWith (short) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |

 **Returns:**
void


---


### setNumberedBulletStyle {#setNumberedBulletStyle}

| Name | Description |
| --- | --- |
| setNumberedBulletStyle (byte) | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |

 **Returns:**
void


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (byte) | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |

 **Returns:**
void


---


