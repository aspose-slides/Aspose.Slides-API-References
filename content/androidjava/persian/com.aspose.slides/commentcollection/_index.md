---
title: CommentCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از نظرات یک نویسنده.
type: docs
url: /fa/com.aspose.slides/commentcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

نمایش‌دهنده یک مجموعه از نظرات یک نویسنده.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که در واقع در مجموعه موجود است را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص شده دریافت می‌کند. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | نظر جدیدی را در انتهای مجموعه اضافه می‌کند. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | نظر مدرن جدیدی را در انتهای مجموعه اضافه می‌کند. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | نظر جدیدی را در ایندکس مشخص شده به مجموعه وارد می‌کند. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | نظر مدرن جدیدی را در ایندکس مشخص شده به مجموعه وارد می‌کند. |
| [toArray()](#toArray--) | آرایه‌ای شامل تمام نظرات ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | آرایه‌ای شامل تمام نظرات از بازه مشخص شده ایجاد و برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در ایندکس مشخص شده در مجموعه حذف می‌کند. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | اولین رخداد نظر مشخص شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نظرات را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | نظری را در مجموعه بر اساس ایندکس پیدا می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه همگام‌سازی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری که در واقع در مجموعه موجود است را برمی‌گرداند. فقط-خواندنی  int .

**برمی‌گرداند:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

عنصر را در ایندکس مشخص شده دریافت می‌کند. فقط-خواندنی [Comment](../../com.aspose.slides/comment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**برمی‌گرداند:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

نظر جدیدی را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن ساده یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید به آن اضافه می‌شود. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**برمی‌گرداند:**
[IComment](../../com.aspose.slides/icomment) - نظر اضافه‌شده.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

نظر مدرن جدیدی را در انتهای مجموعه اضافه می‌کند.

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


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن ساده یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید به آن اضافه می‌شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکل روی اسلاید که نظر مدرن جدید به آن مرتبط است. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**برمی‌گرداند:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن اضافه‌شده.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

نظر جدیدی را در ایندکس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که باید نظر در آن وارد شود. |
| text | java.lang.String | متن ساده یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید به آن اضافه می‌شود. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**برمی‌گرداند:**
[IComment](../../com.aspose.slides/icomment) - نظر واردشده.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

نظر مدرن جدیدی را در ایندکس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که باید نظر مدرن در آن وارد شود. |
| text | java.lang.String | متن ساده یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید به آن اضافه می‌شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکل روی اسلاید که نظر مدرن جدید به آن مرتبط است. |
| position | android.graphics.PointF | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**برمی‌گرداند:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن واردشده.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

آرایه‌ای شامل تمام نظرات ایجاد و برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.slides.IComment[] - آرایه‌ای از [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

آرایه‌ای شامل تمام نظرات از بازه مشخص شده ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین نظری که باید برگردانده شود. |
| count | int | تعداد نظراتی که باید برگردانده شود. |

**برمی‌گرداند:**
com.aspose.slides.IComment[] - آرایه‌ای از [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر را در ایندکس مشخص شده در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنا برای عنصر مورد حذف. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

اولین رخداد نظر مشخص شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | نظری برای حذف از مجموعه. |

### clear() {#clear--}
```
public final void clear()
```

تمام نظرات را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - یک java.util.Iterator برای کل مجموعه.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

نظری را در مجموعه بر اساس ایندکس پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| idx | int | ایندکس یکتای نظری که باید پیدا شود  int . |

**برمی‌گرداند:**
[IComment](../../com.aspose.slides/icomment) - نظر یافت‌شده یا null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا نه. فقط-خواندنی  boolean .

**برمی‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه همگام‌سازی را برمی‌گرداند. فقط-خواندنی  Object .

**برمی‌گرداند:**
java.lang.Object