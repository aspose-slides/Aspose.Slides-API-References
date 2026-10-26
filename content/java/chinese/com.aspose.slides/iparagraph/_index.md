---
title: IParagraph
second_title: Aspose.Slides for Java API 参考
description: 表示一段文本。
type: docs
url: /zh/com.aspose.slides/iparagraph/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

表示一段文本。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPortions()](#getPortions--) | 返回文本片段的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式对象。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并具有相同格式的运行。 |
| [getText()](#getText--) | 获取或设置段落的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置段落的纯文本。 |
| [getRect()](#getRect--) | 获取限定段落的矩形坐标。 |
| [getLinesCount()](#getLinesCount--) | 获取段落中的行数。 |
| [getImage()](#getImage--) | 返回段落的图像。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回按指定比例缩放的段落图像。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最后一个片段后插入另一个片段时要使用的片段属性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最后一个片段后插入另一个片段时要使用的片段属性。 |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


返回文本片段的集合。只读 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**返回：**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


返回此段落的格式对象。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


合并具有相同格式的运行。

### getText() {#getText--}
```
public abstract String getText()
```


获取或设置段落的纯文本。读/写 String。

值：文本。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


获取或设置段落的纯文本。读/写 String。

值：文本。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


获取限定段落的矩形坐标。该矩形包括段落中的所有文本行，包括空行。

**返回：**
java.awt.geom.Rectangle2D.Float - Rectangle that bounds paragraph java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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


**返回：**
int - 段落中的行数
### getImage() {#getImage--}
```
public abstract IImage getImage()
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


**返回：**
[IImage](../../com.aspose.slides/iimage) - 包含渲染后段落的图像，如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时发生错误，则返回 null。
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | 应用于段落图像的水平缩放因子。 |
| scaleY | float | 应用于段落图像的垂直缩放因子。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - 包含渲染后段落的图像，如果在其父集合中找不到段落、没有有效的渲染边界，或在渲染图像时发生错误，则返回 null。
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


指定在最后一个片段后插入另一个片段时要使用的片段属性。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


指定在最后一个片段后插入另一个片段时要使用的片段属性。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |