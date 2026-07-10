---
title: Paragraph
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一段文本。
type: docs
url: /zh/com.aspose.slides/paragraph/
---
**Inheritance:**  
继承：

java.lang.Object

**All Implemented Interfaces:**  
所有实现的接口：

[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject  
```
public final class Paragraph implements IParagraph, IDOMObject
```

表示一段文本。

## Constructors

| Constructor | Description |
| --- | --- |
| [Paragraph()](#Paragraph--) | 使用默认属性初始化 Paragraph 类的新实例。 |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | 复制构造函数，用于初始化 Paragraph 类的新实例。 |

## Methods

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | 返回文本段落的集合。 |
| [getParagraphFormat()](#getParagraphFormat--) | 返回此段落的格式化对象。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并具有相同格式的运行。 |
| [getText()](#getText--) | 获取或设置段落的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置段落的纯文本。 |
| [getRect()](#getRect--) | 获取限定段落的矩形坐标。 |
| [getLinesCount()](#getLinesCount--) | 获取段落中的行数。 |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 指定在最后一个段落后插入新段落时使用的段落属性。 |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 指定在最后一个段落后插入新段落时使用的段落属性。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 返回段落所属的幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回段落所属的演示文稿。 |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

返回文本段落的集合。只读 [IPortionCollection](../../com.aspose.slides/iportioncollection)。

**Returns:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

返回此段落的格式化对象。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

--------------------

格式化对象仅包含当前段落定义的格式化参数，不会应用继承的数据。

若要获取包括继承值在内的有效值，请使用 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 方法。

**Returns:**
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

获取或设置段落的纯文本。读/写 String。

Value: 文本。

**Returns:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

获取或设置段落的纯文本。读/写 String。

Value: 文本。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

获取限定段落的矩形坐标。该矩形包括段落中的所有文本行，包括空行。

**Returns:**
android.graphics.RectF

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

**Returns:**
int - Lines count in a paragraph
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Specifies the portion properties that are to be used if another portion is inserted after the last one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a paragraph. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()

返回段落所属的演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)