---
title: IModernComment
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
description: يمثل تعليقا على شريحة.
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
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getShape()](#getShape--) | إرجاع شكل مرتبط بالتعليق. |
| [getTextSelectionStart()](#getTextSelectionStart--) | إرجاع أو تعيين موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | إرجاع أو تعيين موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | إرجاع أو تعيين طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | إرجاع أو تعيين طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getStatus()](#getStatus--) | إرجاع أو تعيين حالة التعليق. |
| [setStatus(byte value)](#setStatus-byte-) | إرجاع أو تعيين حالة التعليق. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


إرجاع شكل مرتبط بالتعليق. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


إرجاع أو تعيين موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. للقراءة والكتابة int.

**الإرجاع:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


إرجاع أو تعيين موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. للقراءة والكتابة int.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


إرجاع أو تعيين طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. للقراءة والكتابة int.

**الإرجاع:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


إرجاع أو تعيين طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. للقراءة والكتابة int.

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


إرجاع أو تعيين حالة التعليق. للقراءة والكتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**الإرجاع:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


إرجاع أو تعيين حالة التعليق. للقراءة والكتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**المعلمات:**
| معلمة | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |