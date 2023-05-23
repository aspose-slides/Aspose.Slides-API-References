---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
weight: 958
url: /java/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) method which returns a [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) instance.
## Methods

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Returns bullet format of the paragraph. |
| [getDepth()](#getDepth--) | Returns or sets depth of the paragraph. |
| [setDepth(short value)](#setDepth-short-) | Returns or sets depth of the paragraph. |
| [getAlignment()](#getAlignment--) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets the text alignment in a paragraph with no inheritance. |
| [getSpaceWithin()](#getSpaceWithin--) | Returns or sets the amount of space between base lines in a paragraph. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Returns or sets the amount of space between base lines in a paragraph. |
| [getSpaceBefore()](#getSpaceBefore--) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. |
| [getSpaceAfter()](#getSpaceAfter--) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determines whether the East Asian line break is used in a paragraph. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determines whether the East Asian line break is used in a paragraph. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the Right to Left writing is used in a paragraph. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determines whether the Right to Left writing is used in a paragraph. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determines whether the Latin line break is used in a paragraph. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determines whether the Latin line break is used in a paragraph. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determines whether the hanging punctuation is used in a paragraph. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determines whether the hanging punctuation is used in a paragraph. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin in a paragraph with no inheritance. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Returns or sets the left margin in a paragraph with no inheritance. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin in a paragraph with no inheritance. |
| [setMarginRight(float value)](#setMarginRight-float-) | Returns or sets the right margin in a paragraph with no inheritance. |
| [getIndent()](#getIndent--) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [setIndent(float value)](#setIndent-float-) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returns or sets default tabulation size with no inheritance. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Returns or sets default tabulation size with no inheritance. |
| [getTabs()](#getTabs--) | Returns tabulations of a paragraph. |
| [getFontAlignment()](#getFontAlignment--) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Returns or sets a font alignment in a paragraph with no inheritance. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returns default portion format of a paragraph. |
| [getEffective()](#getEffective--) | Gets effective paragraph formatting data with the inheritance applied. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```


Returns bullet format of the paragraph. Read-only [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Returns:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short.

**Returns:**
short
### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```


Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returns or sets the text alignment in a paragraph with no inheritance. Read/write [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


Returns or sets the text alignment in a paragraph with no inheritance. Read/write [TextAlignment](../../com.aspose.slides/textalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float.

**Returns:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```


Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float.

**Returns:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```


Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float.

**Returns:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```


Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```


Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```


Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```


Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```


Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```


Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```


Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```


Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```


Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Returns or sets the left margin in a paragraph with no inheritance. Read/write float.

**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```


Returns or sets the left margin in a paragraph with no inheritance. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Returns or sets the right margin in a paragraph with no inheritance. Read/write float.

**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```


Returns or sets the right margin in a paragraph with no inheritance. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float.

**Returns:**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```


Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Returns or sets default tabulation size with no inheritance. Read/write float.

**Returns:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```


Returns or sets default tabulation size with no inheritance. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```


Returns tabulations of a paragraph. No inheritance applied. Read-only [ITabCollection](../../com.aspose.slides/itabcollection).

**Returns:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```


Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```


Returns default portion format of a paragraph. No inheritance applied. Read-only [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```


Gets effective paragraph formatting data with the inheritance applied.

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
