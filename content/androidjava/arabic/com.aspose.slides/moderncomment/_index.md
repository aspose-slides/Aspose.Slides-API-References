---
title: ModernComment
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل تعليقا على شريحة.
type: docs
url: /ar/com.aspose.slides/moderncomment/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

يمثل تعليقا على شريحة.

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

| الطريقة | الوصف |
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

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**القيمة المرجعة:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**القيمة المرجعة:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


Gets or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**القيمة المرجعة:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


Gets or sets the status of the comment. Read/write [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent_Immediate object. Read-only IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject