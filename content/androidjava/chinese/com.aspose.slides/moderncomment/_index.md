---
title: ModernComment
second_title: Aspose.Slides for Android via Java API 参考
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getShape()](#getShape--) | Returns a shape associated with the comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Gets or sets text selection length in text frame if the comment associated with AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Gets or sets text selection length in text frame if the comment associated with AutoShape. |
| [getStatus()](#getStatus--) | Gets or sets the status of the comment. |
| [setStatus(byte value)](#setStatus-byte-) | Gets or sets the status of the comment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

Returns a shape associated with the comment. Read-only [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**Returns:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**Returns:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

Gets or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Returns:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

Gets or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject