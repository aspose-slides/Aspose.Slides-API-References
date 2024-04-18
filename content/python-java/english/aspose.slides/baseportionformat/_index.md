---
title: BasePortionFormat
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/baseportionformat/
---

## BasePortionFormat class

 Common text portion formatting properties.
 
### getAlternativeLanguageId {#getAlternativeLanguageId}

| Name | Description |
| --- | --- |
| getAlternativeLanguageId() | Returns or sets the Id of an alternative language. Read/write String. |

 **Returns:**
String


---


### getComplexScriptFont {#getComplexScriptFont}

| Name | Description |
| --- | --- |
| getComplexScriptFont() | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getEastAsianFont {#getEastAsianFont}

| Name | Description |
| --- | --- |
| getEastAsianFont() | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getEffectFormat {#getEffectFormat}

| Name | Description |
| --- | --- |
| getEffectFormat() | Returns the text EffectFormat properties. No inheritance applied. Read-only IEffectFormat. |

 **Returns:**
[EffectFormat](../effectformat)


---


### getEscapement {#getEscapement}

| Name | Description |
| --- | --- |
| getEscapement() | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Returns:**
float


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat() | Returns the text FillFormat properties. No inheritance applied. Read-only IFillFormat. |

 **Returns:**
[FillFormat](../fillformat)


---


### getFontBold {#getFontBold}

| Name | Description |
| --- | --- |
| getFontBold() | Determines whether the font is bold. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getFontHeight {#getFontHeight}

| Name | Description |
| --- | --- |
| getFontHeight() | Returns or sets the font height of a portion. Float.NaN means height is undefined and should be inherited from the Master. Read/write float. |

 **Returns:**
float


---


### getFontItalic {#getFontItalic}

| Name | Description |
| --- | --- |
| getFontItalic() | Determines whether the font is itallic. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getFontUnderline {#getFontUnderline}

| Name | Description |
| --- | --- |
| getFontUnderline() | Returns or sets the text underline type. No inheritance applied. Read/write TextUnderlineType. |

 **Returns:**
byte


---


### getHighlightColor {#getHighlightColor}

| Name | Description |
| --- | --- |
| getHighlightColor() | Returns the color used to highlight a text. No inheritance applied. Read-only IColorFormat. |

 **Returns:**
[ColorFormat](../colorformat)


---


### getKerningMinimalSize {#getKerningMinimalSize}

| Name | Description |
| --- | --- |
| getKerningMinimalSize() | Returns or sets the minimal font size, for which kerning should be switched on. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Returns:**
float


---


### getKumimoji {#getKumimoji}

| Name | Description |
| --- | --- |
| getKumimoji() | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getLanguageId {#getLanguageId}

| Name | Description |
| --- | --- |
| getLanguageId() | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |

 **Returns:**
String


---


### getLatinFont {#getLatinFont}

| Name | Description |
| --- | --- |
| getLatinFont() | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getLineFormat {#getLineFormat}

| Name | Description |
| --- | --- |
| getLineFormat() | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only ILineFormat. |

 **Returns:**
[LineFormat](../lineformat)


---


### getNormaliseHeight {#getNormaliseHeight}

| Name | Description |
| --- | --- |
| getNormaliseHeight() | Determines whether the height of a text should be normalized. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getProofDisabled {#getProofDisabled}

| Name | Description |
| --- | --- |
| getProofDisabled() | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getSpacing {#getSpacing}

| Name | Description |
| --- | --- |
| getSpacing() | Returns or sets the intercharacter spacing increment. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Returns:**
float


---


### getStrikethroughType {#getStrikethroughType}

| Name | Description |
| --- | --- |
| getStrikethroughType() | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write TextStrikethroughType. |

 **Returns:**
byte


---


### getSymbolFont {#getSymbolFont}

| Name | Description |
| --- | --- |
| getSymbolFont() | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Returns:**
[FontData](../fontdata)


---


### getTextCapType {#getTextCapType}

| Name | Description |
| --- | --- |
| getTextCapType() | Returns or sets the type of text capitalization. No inheritance applied. Read/write TextCapType. |

 **Returns:**
byte


---


### getUnderlineFillFormat {#getUnderlineFillFormat}

| Name | Description |
| --- | --- |
| getUnderlineFillFormat() | Returns the underline line FillFormat properties. No inheritance applied. Read-only IFillFormat. |

 **Returns:**
[FillFormat](../fillformat)


---


### getUnderlineLineFormat {#getUnderlineLineFormat}

| Name | Description |
| --- | --- |
| getUnderlineLineFormat() | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only ILineFormat. |

 **Returns:**
[LineFormat](../lineformat)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion() |  |

 **Returns:**
long


---


### isHardUnderlineFill {#isHardUnderlineFill}

| Name | Description |
| --- | --- |
| isHardUnderlineFill() | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write NullableBool. |

 **Returns:**
byte


---


### isHardUnderlineLine {#isHardUnderlineLine}

| Name | Description |
| --- | --- |
| isHardUnderlineLine() | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write NullableBool. |

 **Returns:**
byte


---


### setAlternativeLanguageId {#setAlternativeLanguageId}

| Name | Description |
| --- | --- |
| setAlternativeLanguageId(String) | Returns or sets the Id of an alternative language. Read/write String. |


---


### setComplexScriptFont {#setComplexScriptFont}

| Name | Description |
| --- | --- |
| setComplexScriptFont([FontData](../fontdata)) | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setEastAsianFont {#setEastAsianFont}

| Name | Description |
| --- | --- |
| setEastAsianFont([FontData](../fontdata)) | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setEscapement {#setEscapement}

| Name | Description |
| --- | --- |
| setEscapement(float) | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setFontBold {#setFontBold}

| Name | Description |
| --- | --- |
| setFontBold(byte) | Determines whether the font is bold. No inheritance applied. Read/write NullableBool. |


---


### setFontHeight {#setFontHeight}

| Name | Description |
| --- | --- |
| setFontHeight(float) | Returns or sets the font height of a portion. Float.NaN means height is undefined and should be inherited from the Master. Read/write float. |


---


### setFontItalic {#setFontItalic}

| Name | Description |
| --- | --- |
| setFontItalic(byte) | Determines whether the font is itallic. No inheritance applied. Read/write NullableBool. |


---


### setFontUnderline {#setFontUnderline}

| Name | Description |
| --- | --- |
| setFontUnderline(byte) | Returns or sets the text underline type. No inheritance applied. Read/write TextUnderlineType. |


---


### setHardUnderlineFill {#setHardUnderlineFill}

| Name | Description |
| --- | --- |
| setHardUnderlineFill(byte) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write NullableBool. |


---


### setHardUnderlineLine {#setHardUnderlineLine}

| Name | Description |
| --- | --- |
| setHardUnderlineLine(byte) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write NullableBool. |


---


### setKerningMinimalSize {#setKerningMinimalSize}

| Name | Description |
| --- | --- |
| setKerningMinimalSize(float) | Returns or sets the minimal font size, for which kerning should be switched on. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setKumimoji {#setKumimoji}

| Name | Description |
| --- | --- |
| setKumimoji(byte) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write NullableBool. |


---


### setLanguageId {#setLanguageId}

| Name | Description |
| --- | --- |
| setLanguageId(String) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |


---


### setLatinFont {#setLatinFont}

| Name | Description |
| --- | --- |
| setLatinFont([FontData](../fontdata)) | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setNormaliseHeight {#setNormaliseHeight}

| Name | Description |
| --- | --- |
| setNormaliseHeight(byte) | Determines whether the height of a text should be normalized. No inheritance applied. Read/write NullableBool. |


---


### setProofDisabled {#setProofDisabled}

| Name | Description |
| --- | --- |
| setProofDisabled(byte) | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write NullableBool. |


---


### setSpacing {#setSpacing}

| Name | Description |
| --- | --- |
| setSpacing(float) | Returns or sets the intercharacter spacing increment. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setStrikethroughType {#setStrikethroughType}

| Name | Description |
| --- | --- |
| setStrikethroughType(byte) | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write TextStrikethroughType. |


---


### setSymbolFont {#setSymbolFont}

| Name | Description |
| --- | --- |
| setSymbolFont([FontData](../fontdata)) | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setTextCapType {#setTextCapType}

| Name | Description |
| --- | --- |
| setTextCapType(byte) | Returns or sets the type of text capitalization. No inheritance applied. Read/write TextCapType. |


---


