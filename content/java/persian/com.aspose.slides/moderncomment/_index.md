---
title: ModernComment
second_title: مرجع API Aspose.Slides برای جاوا
description: یک نظر را در اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/moderncomment/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

یک نظر در اسلاید را نشان می‌دهد.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getShape()](#getShape--) | یک شکل مرتبط با نظر را برمی‌گرداند. |
| [getTextSelectionStart()](#getTextSelectionStart--) | موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. |
| [getTextSelectionLength()](#getTextSelectionLength--) | طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. |
| [getStatus()](#getStatus--) | وضعیت نظر را دریافت یا تنظیم می‌کند. |
| [setStatus(byte value)](#setStatus-byte-) | وضعیت نظر را دریافت یا تنظیم می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


یک شکل مرتبط با نظر را برمی‌گرداند. فقط خواندنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازگشت:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**بازگشت:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


وضعیت نظر را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**بازگشت:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


وضعیت نظر را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


یک شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject