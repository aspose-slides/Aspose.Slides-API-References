---
title: Paragraph
second_title: Aspose.Slides for Java API 参考
description: 表示一段文本。
type: docs
url: /zh/com.aspose.slides/paragraph/
---
**继承：**
java.lang.Object

**已实现的接口：**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

表示一段文本。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Paragraph()](#Paragraph--) | 使用默认属性初始化 Paragraph 类的新实例。 |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | 复制构造函数，用于初始化 Paragraph 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPortions()](#getPortions--) | 返回文本片段的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式化对象。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并具有相同格式的运行。 |
| [getText()](#getText--) | 获取或设置段落的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置段落的纯文本。 |
| [getRect()](#getRect--) | 获取界定段落的矩形坐标。 |
| [getLinesCount()](#getLinesCount--) | 获取段落中的行数。 |
| [getImage()](#getImage--) | 返回段落的图像。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回按指定比例缩放的段落图像。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最后一个片段后插入另一个片段时要使用的片段属性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最后一个片段后插入另一个片段时要使用的片段属性。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 返回段落的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回段落的父演示文稿。 |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

使用默认属性初始化 Paragraph 类的新实例。

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

复制构造函数，用于初始化 Paragraph 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

返回文本片段的集合。只读 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**返回值：**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

返回此段落的格式化对象。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

--------------------

格式化对象仅包含为当前段落定义的格式化参数，不会应用继承的数据。

若要获取包括继承值在内的有效值，请使用 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法。

**返回值：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

合并具有相同格式的运行。

### getText() {#getText--}
```
public final String getText()
```

获取或设置段落的纯文本。可读写 String。

值：文本。

**返回值：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

获取或设置段落的纯文本。可读写 String。

值：文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

获取界定段落的矩形坐标。该矩形包括段落中的所有文本行，包括空行。

**返回值：**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

获取段落中的行数。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
int - 段落中的行数

### getImage() {#getImage--}
```
public final IImage getImage()
```

返回段落的图像。

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值：**
[IImage](../../com.aspose.slides/iimage) - 包含渲染后段落的图像，如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时出现错误，则为 null。

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

返回按指定比例缩放的段落图像。

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float | 应用于段落图像的水平缩放因子。 |
| scaleY | float | 应用于段落图像的垂直缩放因子。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - 包含渲染后段落的图像，如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时出现错误，则为 null。

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

指定在最后一个片段后插入另一个片段时要使用的片段属性。

**返回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

指定在最后一个片段后插入另一个片段时要使用的片段属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回段落的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回段落的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)