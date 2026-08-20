---
title: IParagraph
second_title: Aspose.Slides for Java API 參考
description: 表示一段文字。
type: docs
url: /zh-hant/com.aspose.slides/iparagraph/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

表示一段文字。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortions()](#getPortions--) | 返回文字片段的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式化物件。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併具有相同格式的文字片段。 |
| [getText()](#getText--) | 取得或設定段落的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定段落的純文字。 |
| [getRect()](#getRect--) | 取得界定段落的矩形座標。 |
| [getLinesCount()](#getLinesCount--) | 取得段落中的行數。 |
| [getImage()](#getImage--) | 返回段落的影像。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回具有指定比例的段落影像。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最後一個片段之後插入另一片段時要使用的片段屬性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最後一個片段之後插入另一片段時要使用的片段屬性。 |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


返回文字片段的集合。唯讀 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**返回：**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


返回此段落的格式化物件。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


合併具有相同格式的文字片段。

### getText() {#getText--}
```
public abstract String getText()
```


取得或設定段落的純文字。可讀寫 String。

值：文字。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


取得或設定段落的純文字。可讀寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


取得界定段落的矩形座標。該矩形包含段落中所有文字行，包括空白行。

**返回：**
java.awt.geom.Rectangle2D.Float - 界定段落的矩形 java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


取得段落中的行數。

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
int - 段落的行數
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


返回段落的影像。

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
[IImage](../../com.aspose.slides/iimage) - 包含已渲染段落的影像；如果在其父集合中找不到段落、沒有有效的渲染範圍，或在渲染影像時發生錯誤，則返回 null。
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


返回具有指定比例的段落影像。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scaleX | float | 套用於段落影像的水平比例因子。 |
| scaleY | float | 套用於段落影像的垂直比例因子。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - 包含已渲染段落的影像；如果在其父集合中找不到段落、沒有有效的渲染範圍，或在渲染影像時發生錯誤，則返回 null。
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


指定在最後一個片段之後插入另一片段時要使用的片段屬性。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


指定在最後一個片段之後插入另一片段時要使用的片段屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |