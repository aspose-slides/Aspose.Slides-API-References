---
title: IBasePortionFormat
second_title: Aspose.Sildes for Java API Reference
description: p
 This class contains the text portion formatting properties.
type: docs
weight: 653
url: /java/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [IPortionFormat\#getEffective](../../com.aspose.slides/iportionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## Methods

| Method | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat properties for text outlining. |
| [getFillFormat()](#getFillFormat--) | Returns the text FillFormat properties. |
| [getEffectFormat()](#getEffectFormat--) | Returns the text EffectFormat properties. |
| [getHighlightColor()](#getHighlightColor--) | Returns the color used to highlight a text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returns the LineFormat properties used to outline underline line. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returns the underline line FillFormat properties. |
| [getFontBold()](#getFontBold--) | Determines whether the font is bold. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determines whether the font is bold. |
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns or sets the text underline type. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returns or sets the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns or sets the type of text capitalization. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returns or sets the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns or sets the strikethrough type of a text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returns or sets the strikethrough type of a text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns or sets the font height of a portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returns or sets the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font info. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font info. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font info. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns or sets the symbolic font info. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returns or sets the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns or sets the superscript or subscript text. |
| [setEscapement(float value)](#setEscapement-float-) | Returns or sets the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns or sets the Id of a proofing language. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returns or sets the Id of a proofing language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns or sets the Id of an alternative language. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returns or sets the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns or sets the intercharacter spacing increment. |
| [setSpacing(float value)](#setSpacing-float-) | Returns or sets the intercharacter spacing increment. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```


Returns the LineFormat properties for text outlining. No inheritance applied. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returns the text FillFormat properties. No inheritance applied. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Returns the text EffectFormat properties. No inheritance applied. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```


Returns the color used to highlight a text. No inheritance applied. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```


Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```


Returns the underline line FillFormat properties. No inheritance applied. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```


Determines whether the font is bold. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```


Determines whether the font is bold. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```


Determines whether the font is itallic. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```


Determines whether the font is itallic. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```


Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```


Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```


Determines whether the height of a text should be normalized. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```


Determines whether the height of a text should be normalized. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```


Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```


Determines whether the text shouldn't be proofed. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Returns or sets the text underline type. No inheritance applied. Read/write [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returns:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```


Returns or sets the text underline type. No inheritance applied. Read/write [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Returns or sets the type of text capitalization. No inheritance applied. Read/write [TextCapType](../../com.aspose.slides/textcaptype).

**Returns:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```


Returns or sets the type of text capitalization. No inheritance applied. Read/write [TextCapType](../../com.aspose.slides/textcaptype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returns:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```


Returns or sets the strikethrough type of a text. No inheritance applied. Read/write [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```


Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```


Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```


Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```


Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Returns or sets the font height of a portion. **Float.NaN** means height is undefined and should be inherited from the Master. Read/write float.

**Returns:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```


Returns or sets the font height of a portion. **Float.NaN** means height is undefined and should be inherited from the Master. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```


Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Returns:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```


Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Returns or sets the minimal font size, for which kerning should be switched on. **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Returns:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```


Returns or sets the minimal font size, for which kerning should be switched on. **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String.

**Returns:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```


Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Returns or sets the Id of an alternative language. Read/write String.

**Returns:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```


Returns or sets the Id of an alternative language. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Returns or sets the intercharacter spacing increment. **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Returns:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```


Returns or sets the intercharacter spacing increment. **Float.NaN** means value is undefined and should be inherited from the Master. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

