---
title: IModernComment
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک نظر در اسلاید.
type: docs
url: /fa/com.aspose.slides/imoderncomment/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

نمایانگر یک نظر در اسلاید.

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
| [getShape()](#getShape--) | باز می‌گرداند shape مرتبط با comment. |
| [getTextSelectionStart()](#getTextSelectionStart--) | مقدار موقعیت شروع انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | مقدار موقعیت شروع انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. |
| [getTextSelectionLength()](#getTextSelectionLength--) | طول انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | طول انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. |
| [getStatus()](#getStatus--) | وضعیت comment را باز می‌گرداند یا تنظیم می‌کند. |
| [setStatus(byte value)](#setStatus-byte-) | وضعیت comment را باز می‌گرداند یا تنظیم می‌کند. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```

باز می‌گرداند shape مرتبط با comment. فقط‌خواندنی [IShape](../../com.aspose.slides/ishape).

**باز می‌گردد:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```

مقدار موقعیت شروع انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**باز می‌گردد:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```

مقدار موقعیت شروع انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```

طول انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**باز می‌گردد:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextCollectionLength(int value)
```

طول انتخاب متن در فریم متن را در صورتی که comment مرتبط با AutoShape باشد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```

وضعیت comment را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**باز می‌گردد:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```

وضعیت comment را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |