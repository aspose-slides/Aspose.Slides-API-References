---
title: IModernComment
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تعليقًا على شريحة.
type: docs
url: /ar/com.aspose.slides/imoderncomment/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

يمثل تعليقًا على شريحة.

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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShape()](#getShape--) | يرجع شكلًا مرتبطًا بالتعليق. |
| [getTextSelectionStart()](#getTextSelectionStart--) | يرجع أو يضبط موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | يرجع أو يضبط موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | يرجع أو يضبط طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | يرجع أو يضبط طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getStatus()](#getStatus--) | يرجع أو يضبط حالة التعليق. |
| [setStatus(byte value)](#setStatus-byte-) | يرجع أو يضبط حالة التعليق. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

يرجع شكلًا مرتبطًا بالتعليق. قراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

يرجع أو يضبط موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قراءة/كتابة int.

**الإرجاع:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

يرجع أو يضبط موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

يرجع أو يضبط طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قراءة/كتابة int.

**الإرجاع:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

يرجع أو يضبط طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

يرجع أو يضبط حالة التعليق. قراءة/كتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**الإرجاع:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

يرجع أو يضبط حالة التعليق. قراءة/كتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |