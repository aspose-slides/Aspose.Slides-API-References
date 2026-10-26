---
title: CommentCollection
second_title: راهنمای API Aspose.Slides برای جاوا
description: نمایش‌دهنده یک مجموعه از نظرات یک نویسنده.
type: docs
url: /fa/com.aspose.slides/commentcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)  
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

نمایش‌دهنده مجموعه‌ای از نظرات یک نویسنده.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری را که واقعاً در مجموعه موجود هستند دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | نظر جدیدی را در انتهای مجموعه اضافه می‌کند. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | نظر مدرن جدیدی را در انتهای مجموعه اضافه می‌کند. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | نظر جدیدی را در مجموعه در ایندکس مشخص‌شده وارد می‌کند. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | نظر مدرن جدیدی را در مجموعه در ایندکس مشخص‌شده وارد می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام نظرات ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام نظرات در بازه مشخص‌شده ایجاد و برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | اولین رخداد نظر مشخص‌شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نظرات را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که به مرور مجموعه می‌پردازد برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | نظر را در مجموعه بر اساس ایندکس پیدا می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه همگام‌سازی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری را که واقعاً در مجموعه موجود هستند دریافت می‌کند. Read-only  int .

**بازگشت:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. Read-only [Comment](../../com.aspose.slides/comment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

نظر جدیدی را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن ساده یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید باید به آن اضافه شود. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - نظر اضافه شده.

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

نظر مدرن جدیدی را در انتهای مجموعه اضافه می‌کند.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن ساده یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید باید به آن اضافه شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی روی اسلاید که نظر مدرن جدید به آن مرتبط است. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن اضافه شده.

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

نظر جدیدی را در مجموعه در ایندکس مشخص‌شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که نظر باید در آن وارد شود. |
| text | java.lang.String | متن ساده یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید باید به آن اضافه شود. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - نظر وارد شده.

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

نظر مدرن جدیدی را در مجموعه در ایندکس مشخص‌شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصری در مجموعه که نظر مدرن باید در آن وارد شود. |
| text | java.lang.String | متن ساده یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید باید به آن اضافه شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی روی اسلاید که یک نظر مدرن جدید به آن مرتبط است. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن وارد شده.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

یک آرایه شامل تمام نظرات ایجاد و برمی‌گرداند.

**بازگشت:**
com.aspose.slides.IComment[] - آرایه‌ای از [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام نظرات در بازه مشخص‌شده ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین نظری که باید برگردانده شود. |
| count | int | تعداد نظراتی که باید برگردانده شود. |

**بازگشت:**
com.aspose.slides.IComment[] - آرایه‌ای از [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنا برای عنصری که باید حذف شود. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

اولین رخداد نظر مشخص‌شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | نظری که باید از مجموعه حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام نظرات را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

یک enumerator که به مرور مجموعه می‌پردازد برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - یک IGenericEnumerator که می‌تواند برای مرور مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - یک java.util.Iterator برای کل مجموعه.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

نظر را در مجموعه بر اساس ایندکس پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| idx | int | ایندکس یکتا برای نظری که باید پیدا شود  int . |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - نظری پیدا‌شده یا null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا خیر. Read-only  boolean .

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه همگام‌سازی را برمی‌گرداند. Read-only  Object .

**بازگشت:**
java.lang.Object