---
title: IModernComment
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک نظر در اسلاید است.
type: docs
url: /fa/com.aspose.slides/imoderncomment/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

نمایانگر یک نظر در اسلاید است.

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
## متدها

| متد | توضیح |
| --- | --- |
| [getShape()](#getShape--) | یک شکل مرتبط با نظر را برمی‌گرداند. |
| [getTextSelectionStart()](#getTextSelectionStart--) | موقعیت شروع انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | موقعیت شروع انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. |
| [getTextSelectionLength()](#getTextSelectionLength--) | طول انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | طول انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. |
| [getStatus()](#getStatus--) | وضعیت نظر را برمی‌گرداند یا تنظیم می‌کند. |
| [setStatus(byte value)](#setStatus-byte-) | وضعیت نظر را برمی‌گرداند یا تنظیم می‌کند. |

### getShape() {#getShape--}
```
public abstract IShape getShape()
```

یک شکل مرتبط با نظر را برمی‌گرداند. فقط خواندنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)

### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

موقعیت شروع انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

موقعیت شروع انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

طول انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. قابل خواندن/نوشتن int.

**بازگشت:**
int

### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```

طول انتخاب متن در فریم متن را برمی‌گرداند یا تنظیم می‌کند اگر نظر با AutoShape مرتبط باشد. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

وضعیت نظر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**بازگشت:**
byte

### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

وضعیت نظر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |