---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 基礎介面，用於包含有效文字片段格式屬性的不可變物件。
type: docs
url: /zh-hant/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

用於包含有效文字片段格式屬性的不可變物件的基礎介面。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 返回文字輪廓的 LineFormat 屬性。 |
| [getFillFormat()](#getFillFormat--) | 返回文字的 FillFormat 屬性。 |
| [getEffectFormat()](#getEffectFormat--) | 返回文字的 EffectFormat 屬性。 |
| [getHighlightColor()](#getHighlightColor--) | 返回用於突出顯示文字的顏色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 返回用於描繪底線的 LineFormat 屬性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 返回底線的 FillFormat 屬性。 |
| [getFontBold()](#getFontBold--) | 判斷字體是否為粗體。 |
| [getFontItalic()](#getFontItalic--) | 判斷字體是否為斜體。 |
| [getKumimoji()](#getKumimoji--) | 判斷數字是否應忽略文字的東方語言特定垂直布局。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 判斷文字的高度是否應標準化。 |
| [getProofDisabled()](#getProofDisabled--) | 判斷文字是否不應校對。 |
| [getFontUnderline()](#getFontUnderline--) | 返回文字底線類型。 |
| [getTextCapType()](#getTextCapType--) | 返回文字大小寫類型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 返回文字的刪除線類型。 |
| [getSmartTagClean()](#getSmartTagClean--) | 判斷智能標記是否應被清除。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 判斷底線樣式是具有自己的 LineFormat 屬性還是繼承自文字的 LineFormat 屬性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 判斷底線樣式是具有自己的 FillFormat 屬性還是繼承自文字的 FillFormat 屬性。 |
| [getFontHeight()](#getFontHeight--) | 返回文字片段的字體高度（點數）。 |
| [getLatinFont()](#getLatinFont--) | 返回拉丁字體資訊。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回東亞字體資訊。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回複雜腳本字體資訊。 |
| [getSymbolFont()](#getSymbolFont--) | 返回符號字體資訊。 |
| [getEscapement()](#getEscapement--) | 返回上標或下標文字。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 返回應開啟字距微調的最小字體大小。 |
| [getLanguageId()](#getLanguageId--) | 返回語言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 返回替代語言的 Id。 |
| [getSpacing()](#getSpacing--) | 返回字符間距增量（點數）。 |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

返回文字輪廓的 LineFormat 屬性。唯讀 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**返回:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

返回文字的 FillFormat 屬性。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

返回文字的 EffectFormat 屬性。唯讀 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**返回:**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

返回用於突出顯示文字的顏色。唯讀 java.lang.Integer。

**返回:**  
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

返回用於描繪底線的 LineFormat 屬性。唯讀 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**返回:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

返回底線的 FillFormat 屬性。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

判斷字體是否為粗體。唯讀 boolean。

**返回:**  
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

判斷字體是否為斜體。唯讀 boolean。

**返回:**  
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

判斷數字是否應忽略文字的東方語言特定垂直布局。唯讀 boolean。

**返回:**  
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

判斷文字的高度是否應標準化。唯讀 boolean。

**返回:**  
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

判斷文字是否不應校對。唯讀 boolean。

**返回:**  
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

返回文字底線類型。唯讀 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**返回:**  
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

返回文字大小寫類型。唯讀 [TextCapType](../../com.aspose.slides/textcaptype)。

**返回:**  
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

返回文字的刪除線類型。唯讀 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**返回:**  
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

判斷智能標記是否應被清除。唯讀 boolean。

**返回:**  
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

判斷底線樣式是具有自己的 LineFormat 屬性還是繼承自文字的 LineFormat 屬性。唯讀 boolean。

**返回:**  
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

判斷底線樣式是具有自己的 FillFormat 屬性還是繼承自文字的 FillFormat 屬性。唯讀 boolean。

**返回:**  
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

返回文字片段的字體高度（點數）。唯讀 float。

**返回:**  
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

返回拉丁字體資訊。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

返回東亞字體資訊。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

返回複雜腳本字體資訊。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

返回符號字體資訊。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**  
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

返回上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。唯讀 float。

**返回:**  
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

返回應開啟字距微調的最小字體大小。唯讀 float。

**返回:**  
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

返回語言的 Id。唯讀 String。

**返回:**  
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

返回替代語言的 Id。唯讀 String。

**返回:**  
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

返回字符間距增量（點數）。唯讀 float。

**返回:**  
float