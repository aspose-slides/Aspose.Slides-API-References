---
title: Paragraph
second_title: Aspose.Slides for Java API 參考
description: 表示一段文字。
type: docs
url: /zh-hant/com.aspose.slides/paragraph/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject  
```
public final class Paragraph implements IParagraph, IDOMObject
```

表示一段文字。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Paragraph()](#Paragraph--) | 使用預設屬性初始化 Paragraph 類別的新執行個體。 |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | 拷貝建構函式，初始化 Paragraph 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortions()](#getPortions--) | 傳回文字片段的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 傳回此段落的格式物件。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併具有相同格式的執行段。 |
| [getText()](#getText--) | 取得或設定段落的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定段落的純文字。 |
| [getRect()](#getRect--) | 取得界定段落的矩形座標。 |
| [getLinesCount()](#getLinesCount--) | 取得段落中的行數。 |
| [getImage()](#getImage--) | 傳回段落的影像。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 傳回使用指定比例的段落影像。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最後一個部分之後插入另一個部分時要使用的部分屬性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最後一個部分之後插入另一個部分時要使用的部分屬性。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 傳回段落的母投影片。 |
| [getPresentation()](#getPresentation--) | 傳回段落的母簡報。 |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

使用預設屬性初始化 Paragraph 類別的新執行個體。

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

拷貝建構函式，初始化 Paragraph 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

傳回文字片段的集合。唯讀 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**傳回:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

傳回此段落的格式物件。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

--------------------

格式物件僅包含目前段落所定義的格式參數，未套用繼承的資料。

若要取得包含繼承值的有效值，請使用 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法。

**傳回:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

合併具有相同格式的執行段。

### getText() {#getText--}
```
public final String getText()
```

取得或設定段落的純文字。讀寫 String。

值：文字。

**傳回:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

取得或設定段落的純文字。讀寫 String。

值：文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

取得界定段落的矩形座標。該矩形包含段落中所有文字行，包括空白行。

**傳回:**
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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

**傳回:**
int - 段落中的行數

### getImage() {#getImage--}
```
public final IImage getImage()
```

傳回段落的影像。

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

**傳回:**
[IImage](../../com.aspose.slides/iimage) - 包含已渲染段落的影像；若在其父集合中找不到段落、沒有有效的渲染邊界，或在渲染影像時發生錯誤，則返回 null。

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

傳回使用指定比例的段落影像。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scaleX | float | 套用於段落影像的水平比例因子。 |
| scaleY | float | 套用於段落影像的垂直比例因子。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - 包含已渲染段落的影像；若在其父集合中找不到段落、沒有有效的渲染邊界，或在渲染影像時發生錯誤，則返回 null。

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

指定在最後一個部分之後插入另一個部分時要使用的部分屬性。

**傳回:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

指定在最後一個部分之後插入另一個部分時要使用的部分屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回段落的母投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回段落的母簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回:**
[IPresentation](../../com.aspose.slides/ipresentation)