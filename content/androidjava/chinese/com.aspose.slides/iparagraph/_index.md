---
title: IParagraph
second_title: Aspose.Slides for Android via Java API 参考
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
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式化对象。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并具有相同格式的运行。 |
| [getText()](#getText--) | 获取或设置段落的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置段落的纯文本。 |
| [getRect()](#getRect--) | 获取包围段落的矩形坐标。 |
| [getLinesCount()](#getLinesCount--) | 获取段落中的行数。 |
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

返回此段落的格式化对象。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

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

获取或设置段落的纯文本。读写 String。

值：文本。

**返回：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

获取或设置段落的纯文本。读写 String。

值：文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

获取包围段落的矩形坐标。该矩形包括段落中的所有行，包括空行。

**返回：**
android.graphics.RectF - 包围段落的矩形 android.graphics.RectF

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

**Returns:**
int - Lines count in a paragraph
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

指定在最后一个片段后插入另一个片段时要使用的片段属性。

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
Specifies the portion properties that are to be used if another portion is inserted after the last one.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |