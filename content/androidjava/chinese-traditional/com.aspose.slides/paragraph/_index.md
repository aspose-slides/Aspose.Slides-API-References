---
title: Paragraph
second_title: 適用於 Android 的 Aspose.Slides Java API 參考
description: 表示一段文字。
type: docs
url: /zh-hant/com.aspose.slides/paragraph/
---
**繼承：**
java.lang.Object

**所有已實作介面：**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

表示一段文字。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [Paragraph()](#Paragraph--) | 使用預設屬性初始化 Paragraph 類別的新執行個體。 |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | 複製建構子，初始化 Paragraph 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPortions()](#getPortions--) | 傳回文字片段的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 傳回此段落的格式化物件。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併具有相同格式的執行段。 |
| [getText()](#getText--) | 取得或設定段落的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定段落的純文字。 |
| [getRect()](#getRect--) | 取得限定段落的矩形座標。 |
| [getLinesCount()](#getLinesCount--) | 取得段落的行數。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定當在最後一個片段之後插入另一個片段時使用的片段屬性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定當在最後一個片段之後插入另一個片段時使用的片段屬性。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 傳回段落的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回段落的父簡報。 |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

使用預設屬性初始化 Paragraph 類別的新執行個體。

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

複製建構子，初始化 Paragraph 類別的新執行個體。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

傳回文字片段的集合。唯讀 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**傳回值：**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

傳回此段落的格式化物件。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

--------------------

此格式化物件僅包含針對目前段落定義的格式參數，不會套用繼承的資料。

若要取得包含繼承值的有效值，請使用 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法。

**傳回值：**
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

取得或設定段落的純文字。可讀寫 String。

值：文字。

**傳回值：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

取得或設定段落的純文字。可讀寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

取得限定段落的矩形座標。該矩形包含段落中所有文字行，包括空行。

**傳回值：**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

取得段落的行數。

--------------------

> ```
> 範例：
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

**傳回值：**
int - 段落的行數
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

指定當在最後一個片段之後插入另一個片段時使用的片段屬性。

**傳回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

指定當在最後一個片段之後插入另一個片段時使用的片段屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回段落的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回段落的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值：**
[IPresentation](../../com.aspose.slides/ipresentation)