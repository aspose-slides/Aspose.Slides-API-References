---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 用于包含有效文本段格式属性的不可变对象的基接口。
type: docs
url: /zh/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

用于包含有效文本段格式属性的不可变对象的基接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 返回文本描边的 LineFormat 属性。 |
| [getFillFormat()](#getFillFormat--) | 返回文本 FillFormat 属性。 |
| [getEffectFormat()](#getEffectFormat--) | 返回文本 EffectFormat 属性。 |
| [getHighlightColor()](#getHighlightColor--) | 返回用于高亮文本的颜色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 返回用于描绘下划线的 LineFormat 属性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 返回下划线的 FillFormat 属性。 |
| [getFontBold()](#getFontBold--) | 确定字体是否为粗体。 |
| [getFontItalic()](#getFontItalic--) | 确定字体是否为斜体。 |
| [getKumimoji()](#getKumimoji--) | 确定数字是否应忽略文本东亚语言特定的垂直布局。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 确定文本的高度是否应归一化。 |
| [getProofDisabled()](#getProofDisabled--) | 确定文本是否不应进行校对。 |
| [getFontUnderline()](#getFontUnderline--) | 返回文本下划线类型。 |
| [getTextCapType()](#getTextCapType--) | 返回文本大写类型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 返回文本删除线类型。 |
| [getSmartTagClean()](#getSmartTagClean--) | 确定是否应清除智能标签。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 确定下划线样式是拥有自己的 LineFormat 属性还是继承自文本的 LineFormat 属性。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 确定下划线样式是拥有自己的 FillFormat 属性还是继承自文本的 FillFormat 属性。 |
| [getFontHeight()](#getFontHeight--) | 返回文本段的字体高度，单位为点。 |
| [getLatinFont()](#getLatinFont--) | 返回拉丁字体信息。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回东亚字体信息。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回复杂脚本字体信息。 |
| [getSymbolFont()](#getSymbolFont--) | 返回符号字体信息。 |
| [getEscapement()](#getEscapement--) | 返回上标或下标文本。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 返回应开启字距微调的最小字体大小。 |
| [getLanguageId()](#getLanguageId--) | 返回语言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 返回备用语言的 Id。 |
| [getSpacing()](#getSpacing--) | 返回字符间距增量，单位为点。 |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

返回文本描边的 LineFormat 属性。只读 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**返回：**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

返回文本 FillFormat 属性。只读 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

返回文本 EffectFormat 属性。只读 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。

**返回：**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

返回用于高亮文本的颜色。只读 java.lang.Integer。

**返回：**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

返回用于描绘下划线的 LineFormat 属性。只读 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。

**返回：**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

返回下划线的 FillFormat 属性。只读 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

确定字体是否为粗体。只读 boolean。

**返回：**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

确定字体是否为斜体。只读 boolean。

**返回：**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

确定数字是否应忽略文本东亚语言特定的垂直布局。只读 boolean。

**返回：**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

确定文本的高度是否应归一化。只读 boolean。

**返回：**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

确定文本是否不应进行校对。只读 boolean。

**返回：**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

返回文本下划线类型。只读 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**返回：**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

返回文本大写类型。只读 [TextCapType](../../com.aspose.slides/textcaptype)。

**返回：**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

返回文本删除线类型。只读 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**返回：**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

确定是否应清除智能标签。只读 boolean。

**返回：**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

确定下划线样式是拥有自己的 LineFormat 属性还是继承自文本的 LineFormat 属性。只读 boolean。

**返回：**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

确定下划线样式是拥有自己的 FillFormat 属性还是继承自文本的 FillFormat 属性。只读 boolean。

**返回：**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

返回文本段的字体高度，单位为点。只读 float。

**返回：**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

返回拉丁字体信息。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

返回东亚字体信息。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

返回复杂脚本字体信息。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

返回符号字体信息。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

返回上标或下标文本。取值范围为 -100%（下标）至 100%（上标）。只读 float。

**返回：**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

返回应开启字距微调的最小字体大小。只读 float。

**返回：**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

返回语言的 Id。只读 String。

**返回：**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

返回备用语言的 Id。只读 String。

**返回：**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

返回字符间距增量，单位为点。只读 float。

**返回：**
float