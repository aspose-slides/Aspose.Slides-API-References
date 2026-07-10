---
title: BasePortionFormat
second_title: Aspose.Slides Android 版 Java API 参考
description: 通用文本段落格式属性。
type: docs
url: /zh/com.aspose.slides/baseportionformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

通用文本段落格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | 返回用于文本轮廓的 LineFormat 属性。 |
| [getFillFormat()](#getFillFormat--) | 返回文本 FillFormat 属性。 |
| [getEffectFormat()](#getEffectFormat--) | 返回文本 EffectFormat 属性。 |
| [getHighlightColor()](#getHighlightColor--) | 返回用于高亮文本的颜色。 |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 返回用于描绘下划线的 LineFormat 属性。 |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 返回下划线的 FillFormat 属性。 |
| [getFontBold()](#getFontBold--) | 确定字体是否为粗体。 |
| [setFontBold(byte value)](#setFontBold-byte-) | 确定字体是否为粗体。 |
| [getFontItalic()](#getFontItalic--) | 确定字体是否为斜体。 |
| [setFontItalic(byte value)](#setFontItalic-byte-) | 确定字体是否为斜体。 |
| [getKumimoji()](#getKumimoji--) | 确定数字是否应忽略文本东亚语言特定的垂直布局。 |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 确定数字是否应忽略文本东亚语言特定的垂直布局。 |
| [getNormaliseHeight()](#getNormaliseHeight--) | 确定文本的高度是否应标准化。 |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | 确定文本的高度是否应标准化。 |
| [getProofDisabled()](#getProofDisabled--) | 确定文本是否不进行校对。 |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | 确定文本是否不进行校对。 |
| [getFontUnderline()](#getFontUnderline--) | 返回或设置文本下划线类型。 |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | 返回或设置文本下划线类型。 |
| [getTextCapType()](#getTextCapType--) | 返回或设置文本大小写类型。 |
| [setTextCapType(byte value)](#setTextCapType-byte-) | 返回或设置文本大小写类型。 |
| [getStrikethroughType()](#getStrikethroughType--) | 返回或设置文本删除线类型。 |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | 返回或设置文本删除线类型。 |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 确定下划线样式是否拥有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。 |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 确定下划线样式是否拥有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。 |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 确定下划线样式是否拥有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。 |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 确定下划线样式是否拥有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。 |
| [getFontHeight()](#getFontHeight--) | 返回或设置段落的字体高度。 |
| [setFontHeight(float value)](#setFontHeight-float-) | 返回或设置段落的字体高度。 |
| [getLatinFont()](#getLatinFont--) | 返回或设置 Latin 字体信息。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或设置 Latin 字体信息。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或设置 East Asian 字体信息。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或设置 East Asian 字体信息。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或设置复杂脚本字体信息。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或设置复杂脚本字体信息。 |
| [getSymbolFont()](#getSymbolFont--) | 返回或设置符号字体信息。 |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | 返回或设置符号字体信息。 |
| [getEscapement()](#getEscapement--) | 返回或设置上标或下标文本。 |
| [setEscapement(float value)](#setEscapement-float-) | 返回或设置上标或下标文本。 |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 返回或设置应开启字距调整的最小字体尺寸。 |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | 返回或设置应开启字距调整的最小字体尺寸。 |
| [getLanguageId()](#getLanguageId--) | 返回或设置校对语言的 Id。 |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 返回或设置校对语言的 Id。 |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 返回或设置备用语言的 Id。 |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 返回或设置备用语言的 Id。 |
| [getSpacing()](#getSpacing--) | 返回或设置字符间距增量。 |
| [setSpacing(float value)](#setSpacing-float-) | 返回或设置字符间距增量。 |
| [getSpellCheck()](#getSpellCheck--) | 获取或设置一个值，指示文本段落是否启用拼写检查。 |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 获取或设置一个值，指示文本段落是否启用拼写检查。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

返回用于文本轮廓的 LineFormat 属性。不适用继承。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

返回文本 FillFormat 属性。不适用继承。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

返回文本 EffectFormat 属性。不适用继承。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

返回用于高亮文本的颜色。不适用继承。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

返回用于描绘下划线的 LineFormat 属性。不适用继承。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

返回下划线的 FillFormat 属性。不适用继承。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

确定字体是否为粗体。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

确定字体是否为粗体。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

确定字体是否为斜体。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

确定字体是否为斜体。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

确定数字是否应忽略文本东亚语言特定的垂直布局。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

确定数字是否应忽略文本东亚语言特定的垂直布局。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

确定文本的高度是否应标准化。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

确定文本的高度是否应标准化。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

确定文本是否不进行校对。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

确定文本是否不进行校对。不适用继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

返回或设置文本下划线类型。不适用继承。可读写 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**返回：**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

返回或设置文本下划线类型。不适用继承。可读写 [TextUnderlineType](../../com.aspose.slides/textunderlinetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

返回或设置文本大小写类型。不适用继承。可读写 [TextCapType](../../com.aspose.slides/textcaptype)。

**返回：**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

返回或设置文本大小写类型。不适用继承。可读写 [TextCapType](../../com.aspose.slides/textcaptype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

返回或设置文本删除线类型。不适用继承。可读写 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**返回：**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

返回或设置文本删除线类型。不适用继承。可读写 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

确定下划线样式是否拥有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

确定下划线样式是否拥有自己的 LineFormat 属性或从文本的 LineFormat 属性继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

确定下划线样式是否拥有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

确定下划线样式是否拥有自己的 FillFormat 属性或从文本的 FillFormat 属性继承。可读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

返回或设置段落的字体高度。**Float.NaN** 表示高度未定义，应从母版继承。可读写  float 。

**返回：**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

返回或设置段落的字体高度。**Float.NaN** 表示高度未定义，应从母版继承。可读写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

返回或设置 Latin 字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

返回或设置 Latin 字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

返回或设置 East Asian 字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

返回或设置 East Asian 字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

返回或设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

返回或设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

返回或设置符号字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

返回或设置符号字体信息。Null 表示字体未定义，应从母版继承。可读写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

返回或设置上标或下标文本。取值范围 -100%（下标）至 100%（上标）。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**返回：**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

返回或设置上标或下标文本。取值范围 -100%（下标）至 100%（上标）。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

返回或设置应开启字距调整的最小字体尺寸。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**返回：**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

返回或设置应开启字距调整的最小字体尺寸。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

返回或设置校对语言的 Id。用于检查拼写和语法。可读写 String。

**返回：**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

返回或设置校对语言的 Id。用于检查拼写和语法。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

返回或设置备用语言的 Id。可读写 String。

**返回：**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

返回或设置备用语言的 Id。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

返回或设置字符间距增量。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**返回：**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

返回或设置字符间距增量。**Float.NaN** 表示值未定义，应从母版继承。可读写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

获取或设置一个值，指示文本段落是否启用拼写检查。当此属性设为 false 时，文本元素的拼写检查被抑制。设为 true 时，允许拼写检查。默认值为 false 。

**返回：**
boolean

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 访问第一张幻灯片中第一个形状内的第一段文本
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 为此文本段落启用拼写检查
>      portion.getPortionFormat().setSpellCheck(true);
>      // 保存修改后的演示文稿
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Returns:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)


Gets or sets a value indicating whether spell checking is enabled for the text portion. When this property is set to false, spelling checks for text elements are suppressed. When set to true, spell checking is allowed. Default value is  false .


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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |