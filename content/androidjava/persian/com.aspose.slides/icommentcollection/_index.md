---
title: ICommentCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از نظرات یک نویسنده است.
type: docs
url: /fa/com.aspose.slides/icommentcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

نمایانگر مجموعه‌ای از نظرات یک نویسنده است.
## Methods

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Add new comment at the end of a collection. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Add new modern comment at the end of a collection. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Insert new comment to a collection at the specified index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Insert new modern comment to a collection at the specified index. |
| [toArray()](#toArray--) | Creates and returns an array with all comments. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all comments from the specified range. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index in a collection. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Removes the first occurrence of the specified comment in a collection. |
| [clear()](#clear--) | Removes all comments from a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Gets the element at the specified index. فقط-خواندنی [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Add new comment at the end of a collection.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی سادهٔ یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید در یک ارائه که نظرسازی جدید به آن اضافه می‌شود. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظرسازی جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظرسازی. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - Added comment.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Add new modern comment at the end of a collection.

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

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی سادهٔ یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید در یک ارائه که نظرسازی مدرن جدید به آن اضافه می‌شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی روی اسلاید که نظرسازی مدرن جدید به آن مرتبط است. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظرسازی مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظرسازی مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Added modern comment.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Insert new comment to a collection at the specified index.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که نظر باید در آن وارد شود. |
| text | java.lang.String | متنی سادهٔ یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید در یک ارائه که نظرسازی جدید به آن اضافه می‌شود. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظرسازی جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظرسازی. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - Inserted comment.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Insert new modern comment to a collection at the specified index.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که نظرسازی مدرن باید در آن وارد شود. |
| text | java.lang.String | متنی سادهٔ یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلاید در یک ارائه که نظرسازی مدرن جدید به آن اضافه می‌شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی روی اسلاید که نظرسازی مدرن جدید به آن مرتبط است. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظرسازی مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظرسازی مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Inserted modern comment.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Creates and returns an array with all comments.

**بازگشت:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Creates and returns an array with all comments from the specified range.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین نظری که باید بازگردانده شود. |
| count | int | تعداد نظراتی که باید بازگردانده شوند. |

**بازگشت:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index in a collection.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر مبنا برای عنصری که باید حذف شود. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Removes the first occurrence of the specified comment in a collection.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | نظری که باید از مجموعه حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all comments from a collection.