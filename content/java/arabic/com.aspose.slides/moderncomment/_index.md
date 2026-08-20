---
title: ModernComment
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة جافا
description: يمثل تعليقًا على شريحة.
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

| الطريقة | الوصف |
| --- | --- |
| [getShape()](#getShape--) | إرجاع شكل مرتبط بالتعليق. |
| [getTextSelectionStart()](#getTextSelectionStart--) | يحصل أو يعيّن موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | يحصل أو يعيّن موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | يحصل أو يعيّن طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | يحصل أو يعيّن طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. |
| [getStatus()](#getStatus--) | يحصل أو يعيّن حالة التعليق. |
| [setStatus(byte value)](#setStatus-byte-) | يحصل أو يعيّن حالة التعليق. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```

إرجاع شكل مرتبط بالتعليق. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```

يحصل أو يعيّن موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قابل للقراءة والكتابة int.

**الإرجاع:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```

يحصل أو يعيّن موضع البداية لتحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قابل للقراءة والكتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```

يحصل أو يعيّن طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قابل للقراءة والكتابة int.

**الإرجاع:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```

يحصل أو يعيّن طول تحديد النص في إطار النص إذا كان التعليق مرتبطًا بـ AutoShape. قابل للقراءة والكتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```

يحصل أو يعيّن حالة التعليق. قابل للقراءة والكتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**الإرجاع:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```

يحصل أو يعيّن حالة التعليق. قابل للقراءة والكتابة [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject