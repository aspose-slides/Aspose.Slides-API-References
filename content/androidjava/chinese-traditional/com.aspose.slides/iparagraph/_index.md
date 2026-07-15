---
title: IParagraph
second_title: Aspose.Slides for Android via Java API 參考
description: 表示文字段落。
type: docs
url: /zh-hant/com.aspose.slides/iparagraph/
---
**已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

表示文字段落。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPortions()](#getPortions--) | 返回文字部分的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式化對象。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併具有相同格式的執行。 |
| [getText()](#getText--) | 取得或設定段落的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定段落的純文字。 |
| [getRect()](#getRect--) | 取得段落外接矩形的座標。 |
| [getLinesCount()](#getLinesCount--) | 取得段落的行數。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最後一個部分之後插入另一部分時要使用的部分屬性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最後一個部分之後插入另一部分時要使用的部分屬性。 |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

返回文字部分的集合。唯讀 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**返回值：**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

返回此段落的格式化對象。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回值：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

合併具有相同格式的執行。

### getText() {#getText--}
```
public abstract String getText()
```

取得或設定段落的純文字。讀/寫 String。

值：文字。

**返回值：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

取得或設定段落的純文字。讀/寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

取得段落外接矩形的座標。該矩形包含段落中所有文字行，包括空白行。

**返回值：**
android.graphics.RectF - 包圍段落的矩形 android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

取得段落的行數。

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
int - 段落中的行數

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

指定在最後一個部分之後插入另一部分時要使用的部分屬性。

**返回值：**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

指定在最後一個部分之後插入另一部分時要使用的部分屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |