---
title: ModernComment
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片上的注释。
type: docs
url: /zh/com.aspose.slides/moderncomment/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**所有实现的接口:**  
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject  
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

表示幻灯片上的注释。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShape()](#getShape--) | 返回与该注释关联的形状。 |
| [getTextSelectionStart()](#getTextSelectionStart--) | 获取或设置如果注释关联到 AutoShape 时文本框中文本选择的起始位置。 |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | 获取或设置如果注释关联到 AutoShape 时文本框中文本选择的起始位置。 |
| [getTextSelectionLength()](#getTextSelectionLength--) | 获取或设置如果注释关联到 AutoShape 时文本框中文本选择的长度。 |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | 获取或设置如果注释关联到 AutoShape 时文本框中文本选择的长度。 |
| [getStatus()](#getStatus--) | 获取或设置该注释的状态。 |
| [setStatus(byte value)](#setStatus-byte-) | 获取或设置该注释的状态。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getShape() {#getShape--}
```
public final IShape getShape()
```

返回与该注释关联的形状。只读 [IShape](../../com.aspose.slides/ishape)。

**返回：**  
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

获取或设置如果注释关联到 AutoShape 时文本框中文本选择的起始位置。读/写 int。

**返回：**  
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

获取或设置如果注释关联到 AutoShape 时文本框中文本选择的起始位置。读/写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

获取或设置如果注释关联到 AutoShape 时文本框中文本选择的长度。读/写 int。

**返回：**  
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

获取或设置如果注释关联到 AutoShape 时文本框中文本选择的长度。读/写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

获取或设置该注释的状态。读/写 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**返回：**  
byte

### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

获取或设置该注释的状态。读/写 [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject