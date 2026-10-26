---
title: ParagraphFormat
second_title: Aspose.Slides for Java API 参考
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

此类包含段落格式属性。不同于[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)，此类的所有属性均可写。

--------------------

此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将得到“未定义”的值。要获取包括继承在内的有效格式参数值，需要使用 [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 实例。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | 初始化 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的项目符号格式。 |
| [getDepth()](#getDepth--) | 返回或设置段落的深度。 |
| [setDepth(short value)](#setDepth-short-) | 返回或设置段落的深度。 |
| [getAlignment()](#getAlignment--) | 返回或设置段落中文本对齐方式（无继承）。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或设置段落中文本对齐方式（无继承）。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回或设置段落基线之间的间距。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 返回或设置段落基线之间的间距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回或设置段落首行前的空间（无继承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 返回或设置段落首行前的空间（无继承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回或设置段落末行后的空间（无继承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 返回或设置段落末行后的空间（无继承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 确定段落是否使用东亚换行符。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 确定段落是否使用东亚换行符。 |
| [getRightToLeft()](#getRightToLeft--) | 确定段落是否使用从右到左书写。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 确定段落是否使用从右到左书写。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 确定段落是否使用拉丁换行符。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 确定段落是否使用拉丁换行符。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 确定段落是否使用悬挂标点。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 确定段落是否使用悬挂标点。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置段落左侧边距（无继承）。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 返回或设置段落左侧边距（无继承）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置段落右侧边距（无继承）。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 返回或设置段落右侧边距（无继承）。 |
| [getIndent()](#getIndent--) | 返回或设置段落首行缩进/悬挂缩进（无继承）。 |
| [setIndent(float value)](#setIndent-float-) | 返回或设置段落首行缩进/悬挂缩进（无继承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回或设置默认制表位大小（无继承）。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 返回或设置默认制表位大小（无继承）。 |
| [getTabs()](#getTabs--) | 返回段落的制表位。 |
| [getFontAlignment()](#getFontAlignment--) | 返回或设置段落中的字体对齐方式（无继承）。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 返回或设置段落中的字体对齐方式（无继承）。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的默认文本段格式。 |
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


返回或设置段落的深度。值 0 表示未定义的值。读写 short 。

**返回：**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


返回或设置段落的深度。值 0 表示未定义的值。读写 short 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


返回或设置段落中文本对齐方式（无继承）。读写 [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a PPTX file
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accessing first slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accessing the first and second placeholder in the slide and typecasting it as AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Change the text in both placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Getting the first paragraph of the placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligning the text paragraph to center
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Writing the presentation as a PPTX file
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


返回或设置段落中文本对齐方式（无继承）。读写 [TextAlignment](../../com.aspose.slides/textalignment)。

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // 实例化一个表示 PPTX 文件的 Presentation 对象
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 访问第一个幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 访问幻灯片中的第一个和第二个占位符，并将其强制转换为 AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 更改两个占位符中的文本
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 获取占位符的第一个段落
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 将文本段落对齐到中心
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // 将演示文稿写入 PPTX 文件
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


返回或设置段落基线之间的间距。正值表示百分比，负值表示点数大小。未应用继承。读写 float 。

**返回：**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


返回或设置段落基线之间的间距。正值表示百分比，负值表示点数大小。未应用继承。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


返回或设置段落首行前的空间（无继承）。正值指定空白空间占字体大小的百分比。负值指定空白空间的点数大小。读写 float 。

**返回：**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


返回或设置段落首行前的空间（无继承）。正值指定空白空间占字体大小的百分比。负值指定空白空间的点数大小。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


返回或设置段落末行后的空间（无继承）。正值指定空白空间占字体大小的百分比。负值指定空白空间的点数大小。读写 float 。

**返回：**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


返回或设置段落末行后的空间（无继承）。正值指定空白空间占字体大小的百分比。负值指定空白空间的点数大小。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


确定段落是否使用东亚换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


确定段落是否使用东亚换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


确定段落是否使用从右到左书写。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


确定段落是否使用从右到左书写。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


确定段落是否使用拉丁换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


确定段落是否使用拉丁换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


确定段落是否使用悬挂标点。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


确定段落是否使用悬挂标点。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


返回或设置段落左侧边距（无继承）。读写 float 。

**返回：**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


返回或设置段落左侧边距（无继承）。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


返回或设置段落右侧边距（无继承）。读写 float 。

**返回：**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


返回或设置段落右侧边距（无继承）。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


返回或设置段落首行缩进/悬挂缩进（无继承）。悬挂缩进可使用负值定义。读写 float 。

**返回：**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


返回或设置段落首行缩进/悬挂缩进（无继承）。悬挂缩进可使用负值定义。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


返回或设置默认制表位大小（无继承）。读写 float 。

**返回：**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


返回或设置默认制表位大小（无继承）。读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


返回段落的制表位。未应用继承。只读 [ITabCollection](../../com.aspose.slides/itabcollection)。

**返回：**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


返回或设置段落中的字体对齐方式（无继承）。读写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回：**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


返回或设置段落中的字体对齐方式（无继承）。读写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


返回段落的默认文本段格式。未应用继承。只读 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


获取已应用继承的有效段落格式数据。

--------------------

> ```
> 此示例演示获取一些有效段落格式属性。
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

**返回：**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。只读 long。

**返回：**
long