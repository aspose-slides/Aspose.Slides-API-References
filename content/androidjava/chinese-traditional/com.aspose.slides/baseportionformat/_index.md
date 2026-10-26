---
title: BasePortionFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 共用文字部分格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/baseportionformat/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

共用文字部分格式屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | 返回文字輪廓的 LineFormat 屬性。 |
| [getFillFormat()](#getFillFormat--) | 返回文字的 FillFormat 屬性。 |
| [getEffectFormat()](#getEffectFormat--) | 返回文字的 EffectFormat 屬性。 |
| [getHighlightColor()](#getHighlightColor--) | 返回用於突顯文字的顏色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 返回用於描繪底線的 LineFormat 屬性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 返回底線的 FillFormat 屬性。 |
| [getFontBold()](#getFontBold--) | 判斷字體是否為粗體。 |
| [setFontBold(byte value)](#setFontBold-byte-) | 判斷字體是否為粗體。 |
| [getFontItalic()](#getFontItalic--) | 判斷字體是否為斜體。 |
| [setFontItalic(byte value)](#setFontItalic-byte-) | 判斷字體是否為斜體。 |
| [getKumimoji()](#getKumimoji--) | 判斷數字是否應忽略文字東方語言特定的垂直排版。 |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 判斷數字是否應忽略文字東方語言特定的垂直排版。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 判斷文字的高度是否應正規化。 |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | 判斷文字的高度是否應正規化。 |
| [getProofDisabled()](#getProofDisabled--) | 判斷文字是否不應進行校對。 |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | 判斷文字是否不應進行校對。 |
| [getFontUnderline()](#getFontUnderline--) | 返回或設定文字底線類型。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | 返回或設定文字底線類型。 |
| [getTextCapType()](#getTextCapType--) | 返回或設定文字大小寫類型。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | 返回或設定文字大小寫類型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 返回或設定文字刪除線類型。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | 返回或設定文字刪除線類型。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 判斷底線樣式是否具有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 判斷底線樣式是否具有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 判斷底線樣式是否具有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 判斷底線樣式是否具有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。 |
| [getFontHeight()](#getFontHeight--) | 返回或設定文字部分的字體高度。 |
| [setFontHeight(float value)](#setFontHeight-float-) | 返回或設定文字部分的字體高度。 |
| [getLatinFont()](#getLatinFont--) | 返回或設定 Latin 字型資訊。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或設定 Latin 字型資訊。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或設定 East Asian 字型資訊。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或設定 East Asian 字型資訊。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或設定 complex script 字型資訊。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或設定 complex script 字型資訊。 |
| [getSymbolFont()](#getSymbolFont--) | 返回或設定 symbolic 字型資訊。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | 返回或設定 symbolic 字型資訊。 |
| [getEscapement()](#getEscapement--) | 返回或設定上標或下標文字。 |
| [setEscapement(float value)](#setEscapement-float-) | 返回或設定上標或下標文字。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 返回或設定最小字體尺寸，對此開啟字距調整。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | 返回或設定最小字體尺寸，對此開啟字距調整。 |
| [getLanguageId()](#getLanguageId--) | 返回或設定校對語言的 Id。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 返回或設定校對語言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 返回或設定替代語言的 Id。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 返回或設定替代語言的 Id。 |
| [getSpacing()](#getSpacing--) | 返回或設定字元間距增量。 |
| [setSpacing(float value)](#setSpacing-float-) | 返回或設定字元間距增量。 |
| [getSpellCheck()](#getSpellCheck--) | 取得或設定指示是否為文字部分啟用拼寫檢查的值。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 取得或設定指示是否為文字部分啟用拼寫檢查的值。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回：**
long
### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

傳回 LineFormat 屬性，用於文字輪廓。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

傳回文字的 FillFormat 屬性。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

未套用繼承。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

傳回文字的 EffectFormat 屬性。

**傳回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

未套用繼承。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

傳回用於突顯文字的顏色。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

傳回用於描繪底線的 LineFormat 屬性。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

傳回底線的 FillFormat 屬性。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

判斷字體是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

判斷字體是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

判斷字體是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

判斷字體是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

判斷文字的高度是否應正規化。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
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

判斷文字是否不應進行校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

判斷文字是否不應進行校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

返回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**傳回：**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

返回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

返回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**傳回：**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

返回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

返回或設定文字刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**傳回：**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

返回或設定文字刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

判斷底線樣式是否具有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

判斷底線樣式是否具有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

判斷底線樣式是否具有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

判斷底線樣式是否具有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

返回或設定文字部分的字體高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float 。

**傳回：**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

返回或設定文字部分的字體高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

返回或設定 Latin 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

返回或設定 Latin 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

返回或設定 East Asian 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

返回或設定 East Asian 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

返回或設定 complex script 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

返回或設定 complex script 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

返回或設定 symbolic 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

返回或設定 symbolic 字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

返回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回：**
float
### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

返回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

返回或設定最小字體尺寸，對此開啟字距調整。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回：**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

返回或設定最小字體尺寸，對此開啟字距調整。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

返回或設定校對語言的 Id。用於拼寫和文法檢查。讀寫 String。

**傳回：**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

返回或設定校對語言的 Id。用於拼寫和文法檢查。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

返回或設定替代語言的 Id。讀寫 String。

**傳回：**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

返回或設定替代語言的 Id。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

返回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**傳回：**
float
### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

返回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float 。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

取得或設定指示是否為文字部分啟用拼寫檢查的值。當此屬性設為 false 時，會抑制對文字元素的拼寫檢查。當設為 true 時，允許拼寫檢查。預設值為 false。

--------------------

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

**傳回：**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

取得或設定指示是否為文字部分啟用拼寫檢查的值。當此屬性設為 false 時，會抑制對文字元素的拼寫檢查。當設為 true 時，允許拼寫檢查。預設值為 false。

--------------------

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