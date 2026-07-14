---
title: ModernComment
second_title: مرجع API جاوا برای Aspose.Slides در اندروید
description: نمایانگر یک نظر در اسلاید است.
type: docs
url: /fa/com.aspose.slides/moderncomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**All Implemented Interfaces:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
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
## Methods

| Method | Description |
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

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

**Returns:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


موقعیت شروع انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

**Returns:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


طول انتخاب متن در فریم متن را در صورت ارتباط نظر با AutoShape دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getStatus() {#getStatus--}
```
public final byte getStatus()
```


وضعیت نظر را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Returns:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


وضعیت نظر را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject