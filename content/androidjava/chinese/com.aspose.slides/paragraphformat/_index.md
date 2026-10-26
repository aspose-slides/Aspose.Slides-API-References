---
title: ParagraphFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 此类包含段落格式属性。
type: docs
url: /zh/com.aspose.slides/paragraphformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

此类包含段落格式属性。不同于 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)，此类的所有属性均可写。

--------------------

此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不适用继承，因此在大多数情况下您将获得表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 实例。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | 初始化 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的项目符号格式。 |
| [getDepth()](#getDepth--) | 返回或设置段落的 depth。 |
| [setDepth(short value)](#setDepth-short-) | 返回或设置段落的 depth。 |
| [getAlignment()](#getAlignment--) | 返回或设置段落中无继承的文本对齐方式。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或设置段落中无继承的文本对齐方式。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回或设置段落中基线之间的空间量。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 返回或设置段落中基线之间的空间量。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回或设置段落中首行之前的空间量（无继承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 返回或设置段落中首行之前的空间量（无继承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回或设置段落中最后一行之后的空间量（无继承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 返回或设置段落中最后一行之后的空间量（无继承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 确定段落中是否使用东亚换行。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 确定段落中是否使用东亚换行。 |
| [getRightToLeft()](#getRightToLeft--) | 确定段落中是否使用从右到左书写。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 确定段落中是否使用从右到左书写。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 确定段落中是否使用拉丁换行。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 确定段落中是否使用拉丁换行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 确定段落中是否使用悬挂标点。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 确定段落中是否使用悬挂标点。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置段落中无继承的左边距。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 返回或设置段落中无继承的左边距。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置段落中无继承的右边距。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 返回或设置段落中无继承的右边距。 |
| [getIndent()](#getIndent--) | 返回或设置段落的首行缩进/悬挂缩进（无继承）。 |
| [setIndent(float value)](#setIndent-float-) | 返回或设置段落的首行缩进/悬挂缩进（无继承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回或设置段落中无继承的默认制表符大小。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 返回或设置段落中无继承的默认制表符大小。 |
| [getTabs()](#getTabs--) | 返回段落的制表符。 |
| [getFontAlignment()](#getFontAlignment--) | 返回或设置段落中无继承的字体对齐方式。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 返回或设置段落中无继承的字体对齐方式。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的默认部分格式。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效段落格式数据。 |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

初始化 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 类的新实例。

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

返回段落的项目符号格式。只读 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**返回：**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

返回或设置段落的 depth。值 0 表示未定义值。读/写 short 。

**返回：**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

返回或设置段落的 depth。值 0 表示未定义值。读/写 short 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

返回或设置段落中无继承的文本对齐方式。读/写 [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // 实例化一个表示 PPTX 文件的 Presentation 对象
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 访问第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 访问幻灯片中的第一个和第二个占位符并将其强制转换为 AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 更改两个占位符中的文本
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 获取占位符的第一段落
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 将文本段落对齐到居中
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // 将演示文稿保存为 PPTX 文件
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```
Returns or sets the text alignment in a paragraph with no inheritance. Read/write [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // 实例化一个表示 PPTX 文件的 Presentation 对象
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 访问第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 访问幻灯片中的第一个和第二个占位符并将其强制转换为 AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 更改两个占位符中的文本
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 获取占位符的第一段落
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 将文本段落对齐到居中
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // 将演示文稿保存为 PPTX 文件
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write  float .

**Returns:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Returns:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Returns:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```
Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Returns or sets the left margin in a paragraph with no inheritance. Read/write  float .

**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Returns or sets the left margin in a paragraph with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Returns or sets the right margin in a paragraph with no inheritance. Read/write  float .

**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Returns or sets the right margin in a paragraph with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write  float .

**Returns:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Returns or sets default tabulation size with no inheritance. Read/write  float .

**Returns:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Returns or sets default tabulation size with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Returns tabulations of a paragraph. No inheritance applied. Read-only [ITabCollection](../../com.aspose.slides/itabcollection).

**Returns:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```
Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```
Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```
返回段落的默认部分格式。 不适用继承。 只读 [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

获取已应用继承的有效段落格式数据。

--------------------

> ```
> 此示例演示如何获取一些有效的段落格式属性。
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - 一个 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()

版本。只读 long.

**返回：**
long