---
title: BasePortionFormat
second_title: Aspose.Slides for Java API 參考
description: 共用文字區段格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/baseportionformat/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作介面:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)  
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

共用文字區段格式屬性。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | 傳回用於文字描邊的 LineFormat 屬性。 |
| [getFillFormat()](#getFillFormat--) | 傳回文字的 FillFormat 屬性。 |
| [getEffectFormat()](#getEffectFormat--) | 傳回文字的 EffectFormat 屬性。 |
| [getHighlightColor()](#getHighlightColor--) | 傳回用於標示文字的顏色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 傳回用於描繪底線線條的 LineFormat 屬性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 傳回底線線條的 FillFormat 屬性。 |
| [getFontBold()](#getFontBold--) | 判斷字型是否為粗體。 |
| [setFontBold(byte value)](#setFontBold-byte-) | 判斷字型是否為粗體。 |
| [getFontItalic()](#getFontItalic--) | 判斷字型是否為斜體。 |
| [setFontItalic(byte value)](#setFontItalic-byte-) | 判斷字型是否為斜體。 |
| [getKumimoji()](#getKumimoji--) | 判斷數字是否應忽略文字的東亞語言特定垂直排版。 |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 判斷數字是否應忽略文字的東亞語言特定垂直排版。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 判斷文字的高度是否應正規化。 |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | 判斷文字的高度是否應正規化。 |
| [getProofDisabled()](#getProofDisabled--) | 判斷是否不應進行文字校對。 |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | 判斷是否不應進行文字校對。 |
| [getFontUnderline()](#getFontUnderline--) | 傳回或設定文字底線類型。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | 傳回或設定文字底線類型。 |
| [getTextCapType()](#getTextCapType--) | 傳回或設定文字大小寫類型。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | 傳回或設定文字大小寫類型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 傳回或設定文字刪除線類型。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | 傳回或設定文字刪除線類型。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。 |
| [getFontHeight()](#getFontHeight--) | 傳回或設定區段的字型高度。 |
| [setFontHeight(float value)](#setFontHeight-float-) | 傳回或設定區段的字型高度。 |
| [getLatinFont()](#getLatinFont--) | 傳回或設定拉丁字型資訊。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 傳回或設定拉丁字型資訊。 |
| [getEastAsianFont()](#getEastAsianFont--) | 傳回或設定東亞字型資訊。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 傳回或設定東亞字型資訊。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 傳回或設定複雜文字腳本字型資訊。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 傳回或設定複雜文字腳本字型資訊。 |
| [getSymbolFont()](#getSymbolFont--) | 傳回或設定符號字型資訊。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | 傳回或設定符號字型資訊。 |
| [getEscapement()](#getEscapement--) | 傳回或設定上標或下標文字。 |
| [setEscapement(float value)](#setEscapement-float-) | 傳回或設定上標或下標文字。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 傳回或設定應開啟字距微調的最小字型大小。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | 傳回或設定應開啟字距微調的最小字型大小。 |
| [getLanguageId()](#getLanguageId--) | 傳回或設定校對語言的 Id。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 傳回或設定校對語言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 傳回或設定替代語言的 Id。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 傳回或設定替代語言的 Id。 |
| [getSpacing()](#getSpacing--) | 傳回或設定字元間距增量。 |
| [setSpacing(float value)](#setSpacing-float-) | 傳回或設定字元間距增量。 |
| [getSpellCheck()](#getSpellCheck--) | 取得或設定指示文字區段是否啟用拼寫檢查的值。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 取得或設定指示文字區段是否啟用拼寫檢查的值。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回:**  
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

傳回用於文字描邊的 LineFormat 屬性。未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

傳回文字的 FillFormat 屬性。未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

傳回文字的 EffectFormat 屬性。未套用繼承。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**傳回:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

傳回用於標示文字的顏色。未套用繼承。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

傳回用於描繪底線線條的 LineFormat 屬性。未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

傳回底線線條的 FillFormat 屬性。未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

判斷字型是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

判斷字型是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

判斷字型是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

判斷字型是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

判斷數字是否應忽略文字的東亞語言特定垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

判斷數字是否應忽略文字的東亞語言特定垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

判斷文字的高度是否應正規化。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

判斷文字的高度是否應正規化。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

判斷是否不應進行文字校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

判斷是否不應進行文字校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

傳回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**傳回:**  
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

傳回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

傳回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**傳回:**  
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

傳回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

傳回或設定文字刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**傳回:**  
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

傳回或設定文字刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

傳回或設定區段的字型高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float 。

**傳回:**  
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

傳回或設定區段的字型高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

傳回或設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

傳回或設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

傳回或設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

傳回或設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

傳回或設定複雜文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

傳回或設定複雜文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

傳回或設定符號字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

傳回或設定符號字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

傳回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回:**  
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

傳回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

傳回或設定應開啟字距微調的最小字型大小。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回:**  
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

傳回或設定應開啟字距微調的最小字型大小。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

傳回或設定校對語言的 Id。用於拼寫與文法檢查。讀寫 String。

**傳回:**  
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

傳回或設定校對語言的 Id。用於拼寫與文法檢查。讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

傳回或設定替代語言的 Id。讀寫 String。

**傳回:**  
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

傳回或設定替代語言的 Id。讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

傳回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回:**  
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

傳回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

取得或設定指示文字區段是否啟用拼寫檢查的值。當此屬性設為 false 時，將抑制對文字元素的拼寫檢查。設為 true 時，允許拼寫檢查。預設值為 false 。

**傳回:**  
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

取得或設定指示文字區段是否啟用拼寫檢查的值。當此屬性設為 false 時，將抑制對文字元素的拼寫檢查。設為 true 時，允許拼寫檢查。預設值為 false 。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回:**  
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |