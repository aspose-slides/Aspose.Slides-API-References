---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 包含有效文字段格式屬性的不可變物件之基礎介面。
type: docs
url: /zh-hant/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

不可變物件的基礎介面，此類物件包含有效文字段格式屬性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 傳回用於文字輪廓的 LineFormat 屬性。 |
| [getFillFormat()](#getFillFormat--) | 傳回文字的 FillFormat 屬性。 |
| [getEffectFormat()](#getEffectFormat--) | 傳回文字的 EffectFormat 屬性。 |
| [getHighlightColor()](#getHighlightColor--) | 傳回用於標記文字的顏色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 傳回用於描繪底線的 LineFormat 屬性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 傳回底線的 FillFormat 屬性。 |
| [getFontBold()](#getFontBold--) | 判斷字型是否為粗體。 |
| [getFontItalic()](#getFontItalic--) | 判斷字型是否為斜體。 |
| [getKumimoji()](#getKumimoji--) | 判斷數字是否應忽略文字的東亞語言特定垂直排版。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 判斷文字的高度是否應正規化。 |
| [getProofDisabled()](#getProofDisabled--) | 判斷文字是否不需要校對。 |
| [getFontUnderline()](#getFontUnderline--) | 傳回文字的底線類型。 |
| [getTextCapType()](#getTextCapType--) | 傳回文字的大寫類型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 傳回文字的刪除線類型。 |
| [getSmartTagClean()](#getSmartTagClean--) | 判斷是否應清除智慧標記。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。 |
| [getFontHeight()](#getFontHeight--) | 傳回文字段的字型高度，單位為點。 |
| [getLatinFont()](#getLatinFont--) | 傳回拉丁字型資訊。 |
| [getEastAsianFont()](#getEastAsianFont--) | 傳回東亞字型資訊。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 傳回複雜腳本字型資訊。 |
| [getSymbolFont()](#getSymbolFont--) | 傳回符號字型資訊。 |
| [getEscapement()](#getEscapement--) | 傳回上標或下標文字。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 傳回最佳字距調整的最小字型大小。 |
| [getLanguageId()](#getLanguageId--) | 傳回語言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 傳回替代語言的 Id。 |
| [getSpacing()](#getSpacing--) | 傳回字元間距增量，單位為點。 |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```


傳回用於文字輪廓的 LineFormat 屬性。只讀 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


傳回文字的 FillFormat 屬性。只讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


傳回文字的 EffectFormat 屬性。只讀 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**Returns:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```


傳回用於標記文字的顏色。只讀 java.awt.Color。

**Returns:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```


傳回用於描繪底線的 LineFormat 屬性。只讀 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**Returns:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```


傳回底線的 FillFormat 屬性。只讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```


判斷字型是否為粗體。只讀 boolean。

**Returns:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```


判斷字型是否為斜體。只讀 boolean。

**Returns:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```


判斷數字是否應忽略文字的東亞語言特定垂直排版。只讀 boolean。

**Returns:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```


判斷文字的高度是否應正規化。只讀 boolean。

**Returns:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```


判斷文字是否不需要校對。只讀 boolean。

**Returns:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```


傳回文字的底線類型。只讀 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**Returns:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```


傳回文字的大寫類型。只讀 [TextCapType](../../com.aspose.slides/textcaptype)。

**Returns:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```


傳回文字的刪除線類型。只讀 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**Returns:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


判斷是否應清除智慧標記。只讀 boolean。

**Returns:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```


判斷底線樣式是否擁有自己的 LineFormat 屬性，或繼承自文字的 LineFormat 屬性。只讀 boolean。

**Returns:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```


判斷底線樣式是否擁有自己的 FillFormat 屬性，或繼承自文字的 FillFormat 屬性。只讀 boolean。

**Returns:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```


傳回文字段的字型高度，單位為點。只讀 float。

**Returns:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


傳回拉丁字型資訊。只讀 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


傳回東亞字型資訊。只讀 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


傳回複雜腳本字型資訊。只讀 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```


傳回符號字型資訊。只讀 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```


傳回上標或下標文字。值範圍從 -100%（下標）到 100%（上標）。只讀 float。

**Returns:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```


傳回最佳字距調整的最小字型大小。只讀 float。

**Returns:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```


傳回語言的 Id。只讀 String。

**Returns:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```


傳回替代語言的 Id。只讀 String。

**Returns:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```


傳回字元間距增量，單位為點。只讀 float。

**Returns:**
float