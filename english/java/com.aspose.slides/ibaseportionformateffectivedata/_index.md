---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description:  Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
weight: 654
url: /java/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Base interface for immutable objects which contain effective text portion formatting properties.
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
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns the strikethrough type of a text. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns the Id of a language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns the intercharacter spacing increment. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


Returns the LineFormat properties for text outlining. Read-only [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Returns the text FillFormat properties. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Returns the text EffectFormat properties. Read-only [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Returns:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


Returns the color used to highlight a text. Read-only java.awt.Color.

**Returns:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


Returns the LineFormat properties used to outline underline line. Read-only [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


Returns the underline line FillFormat properties. Read-only [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


Determines whether the font is bold. Read-only boolean.

**Returns:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


Determines whether the font is itallic. Read-only boolean.

**Returns:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


Determines whether the numbers should ignore text eastern language-specific vertical text layout. Read-only boolean.

**Returns:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


Determines whether the height of a text should be normalized. Read-only boolean.

**Returns:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


Determines whether the text shouldn't be proofed. Read-only boolean.

**Returns:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


Returns the text underline type. Read-only [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Returns:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


Returns the type of text capitalization. Read-only [TextCapType](../../com.aspose.slides/textcaptype).

**Returns:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


Returns the strikethrough type of a text. Read-only [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Returns:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Determines whether the smart tag should be cleaned. Read-only boolean.

**Returns:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read-only boolean.

**Returns:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read-only boolean.

**Returns:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


Returns the font height of a portion. Read-only float.

**Returns:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


Returns the Latin font info. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


Returns the East Asian font info. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Returns the complex script font info. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


Returns the symbolic font info. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Read-only float.

**Returns:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


Returns the minimal font size, for which kerning should be switched on. Read-only float.

**Returns:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


Returns the Id of a language. Read-only String.

**Returns:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


Returns the Id of an alternative language. Read-only String.

**Returns:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


Returns the intercharacter spacing increment. Read-only float.

**Returns:**
float
