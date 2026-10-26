---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 此類別包含文字區段格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

此類別包含文字區段格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於返回和操作為特定區段定義的文字區段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會取得表示「未定義」的值。

若要取得包括繼承在內的有效格式參數值，您需要使用 [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法，該方法返回一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 返回文字輪廓的 LineFormat 屬性。 |
| [getFillFormat()](#getFillFormat--) | 返回文字的 FillFormat 屬性。 |
| [getEffectFormat()](#getEffectFormat--) | 返回文字的 EffectFormat 屬性。 |
| [getHighlightColor()](#getHighlightColor--) | 返回用於突出顯示文字的顏色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 返回用於描繪底線的 LineFormat 屬性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 返回底線的 FillFormat 屬性。 |
| [getFontBold()](#getFontBold--) | 判斷字型是否為粗體。 |
| [setFontBold(byte value)](#setFontBold-byte-) | 判斷字型是否為粗體。 |
| [getFontItalic()](#getFontItalic--) | 判斷字型是否為斜體。 |
| [setFontItalic(byte value)](#setFontItalic-byte-) | 判斷字型是否為斜體。 |
| [getKumimoji()](#getKumimoji--) | 判斷數字是否應忽略文字的東方語言特定垂直排版。 |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 判斷數字是否應忽略文字的東方語言特定垂直排版。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 判斷文字的高度是否應正規化。 |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | 判斷文字的高度是否應正規化。 |
| [getProofDisabled()](#getProofDisabled--) | 判斷文字是否不進行校對。 |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | 判斷文字是否不進行校對。 |
| [getFontUnderline()](#getFontUnderline--) | 返回或設定文字底線類型。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | 返回或設定文字底線類型。 |
| [getTextCapType()](#getTextCapType--) | 返回或設定文字大小寫類型。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | 返回或設定文字大小寫類型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 返回或設定文字的刪除線類型。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | 返回或設定文字的刪除線類型。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 判斷底線樣式是否具有自己的 LineFormat 屬性，或是繼承自文字的 LineFormat 屬性。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 判斷底線樣式是否具有自己的 LineFormat 屬性，或是繼承自文字的 LineFormat 屬性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 判斷底線樣式是否具有自己的 FillFormat 屬性，或是繼承自文字的 FillFormat 屬性。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 判斷底線樣式是否具有自己的 FillFormat 屬性，或是繼承自文字的 FillFormat 屬性。 |
| [getFontHeight()](#getFontHeight--) | 返回或設定區段的字型高度。 |
| [setFontHeight(float value)](#setFontHeight-float-) | 返回或設定區段的字型高度。 |
| [getLatinFont()](#getLatinFont--) | 返回或設定拉丁字型資訊。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或設定拉丁字型資訊。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或設定東亞字型資訊。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或設定東亞字型資訊。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或設定複雜腳本字型資訊。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或設定複雜腳本字型資訊。 |
| [getSymbolFont()](#getSymbolFont--) | 返回或設定符號字型資訊。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | 返回或設定符號字型資訊。 |
| [getEscapement()](#getEscapement--) | 返回或設定上標或下標文字。 |
| [setEscapement(float value)](#setEscapement-float-) | 返回或設定上標或下標文字。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 返回或設定字型微調應開啟的最小字型大小。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | 返回或設定字型微調應開啟的最小字型大小。 |
| [getLanguageId()](#getLanguageId--) | 返回或設定校對語言的 Id。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 返回或設定校對語言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 返回或設定替代語言的 Id。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 返回或設定替代語言的 Id。 |
| [getSpacing()](#getSpacing--) | 返回或設定字元間距增量。 |
| [setSpacing(float value)](#setSpacing-float-) | 返回或設定字元間距增量。 |
| [getSpellCheck()](#getSpellCheck--) | 取得或設定指示文字區段是否啟用拼寫檢查的值。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 取得或設定指示文字區段是否啟用拼寫檢查的值。 |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

返回文字輪廓的 LineFormat 屬性。未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回文字的 FillFormat 屬性。未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

返回文字的 EffectFormat 屬性。未套用繼承。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

返回用於突出顯示文字的顏色。未套用繼承。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

返回用於描繪底線的 LineFormat 屬性。未套用繼承。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

返回底線的 FillFormat 屬性。未套用繼承。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

判斷字型是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

判斷字型是否為粗體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

判斷字型是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

判斷字型是否為斜體。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

判斷數字是否應忽略文字的東方語言特定垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

判斷數字是否應忽略文字的東方語言特定垂直排版。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

判斷文字的高度是否應正規化。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

判斷文字的高度是否應正規化。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

判斷文字是否不進行校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

判斷文字是否不進行校對。未套用繼承。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

返回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**返回：**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

返回或設定文字底線類型。未套用繼承。讀寫 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

返回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**返回：**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

返回或設定文字大小寫類型。未套用繼承。讀寫 [TextCapType](../../com.aspose.slides/textcaptype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

返回或設定文字的刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**返回：**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

返回或設定文字的刪除線類型。未套用繼承。讀寫 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

判斷底線樣式是否具有自己的 LineFormat 屬性，或是繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

判斷底線樣式是否具有自己的 LineFormat 屬性，或是繼承自文字的 LineFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

判斷底線樣式是否具有自己的 FillFormat 屬性，或是繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

判斷底線樣式是否具有自己的 FillFormat 屬性，或是繼承自文字的 FillFormat 屬性。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

返回或設定區段的字型高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float。

**返回：**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

返回或設定區段的字型高度。**Float.NaN** 表示高度未定義，應從母版繼承。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

返回或設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

返回或設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

返回或設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

返回或設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

返回或設定複雜腳本字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

返回或設定複雜腳本字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

返回或設定符號字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

返回或設定符號字型資訊。Null 表示字型未定義，應從母版繼承。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

返回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**返回：**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

返回或設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

返回或設定字型微調應開啟的最小字型大小。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**返回：**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

返回或設定字型微調應開啟的最小字型大小。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

返回或設定校對語言的 Id。用於拼寫和文法檢查。讀寫 String。

**返回：**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

返回或設定校對語言的 Id。用於拼寫和文法檢查。讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

返回或設定替代語言的 Id。讀寫 String。

**返回：**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

返回或設定替代語言的 Id。讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

返回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**返回：**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

返回或設定字元間距增量。**Float.NaN** 表示值未定義，應從母版繼承。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

取得或設定指示文字區段是否啟用拼寫檢查的值。當此屬性設定為 false 時，將抑制對文字元素的拼寫檢查。設定為 true 時，允許拼寫檢查。預設值為 false。

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 存取第一張投影片上第一個圖形內的第一段文字
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 為此文字區段啟用拼寫檢查
>      portion.getPortionFormat().setSpellCheck(true);
>      // 儲存已修改的簡報
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

取得或設定指示文字區段是否啟用拼寫檢查的值。當此屬性設定為 false 時，將抑制對文字元素的拼寫檢查。設定為 true 時，允許拼寫檢查。預設值為 false。

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 存取第一張投影片上第一個圖形內的第一段文字
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 為此文字區段啟用拼寫檢查
>      portion.getPortionFormat().setSpellCheck(true);
>      // 儲存已修改的簡報
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |