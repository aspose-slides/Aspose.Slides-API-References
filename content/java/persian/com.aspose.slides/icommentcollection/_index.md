---
title: ICommentCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر مجموعه‌ای از نظرات یک نویسنده است.
type: docs
url: /fa/com.aspose.slides/icommentcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

نمایندهٔ مجموعه‌ای از نظرات یک نویسنده است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص‌شده دریافت می‌کند. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | نظر جدید را در انتهای مجموعه اضافه می‌کند. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | نظر مدرن جدید را در انتهای مجموعه اضافه می‌کند. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | نظر جدید را در اندیس مشخص‌شده به مجموعه وارد می‌کند. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | نظر مدرن جدید را در اندیس مشخص‌شده به مجموعه وارد می‌کند. |
| [toArray()](#toArray--) | آرایه‌ای شامل تمام نظرات را ایجاد و باز می‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | آرایه‌ای شامل تمام نظرات از بازهٔ مشخص‌شده را ایجاد و باز می‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس مشخص‌شده در مجموعه حذف می‌کند. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | اولین وقوع نظر مشخص‌شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نظرات را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

عنصر را در اندیس مشخص‌شده دریافت می‌کند. فقط خواندنی [IComment](../../com.aspose.slides/icomment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

نظر جدید را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن سادهٔ یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید باید به آن اضافه شود. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - نظر اضافه‌شده.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

نظر مدرن جدید را در انتهای مجموعه اضافه می‌کند.

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
| text | java.lang.String | متن سادهٔ یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید باید به آن اضافه شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکل روی اسلاید که نظر مدرن جدید به آن مرتبط است. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن اضافه‌شده.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

نظر جدید را در اندیس مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصری در مجموعه که نظر باید در آن وارد شود. |
| text | java.lang.String | متن سادهٔ یک نظر جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر جدید باید به آن اضافه شود. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر. |

**بازگشت:**
[IComment](../../com.aspose.slides/icomment) - نظر وارد‌شده.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

نظر مدرن جدید را در اندیس مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصری در مجموعه که نظر مدرن باید در آن وارد شود. |
| text | java.lang.String | متن سادهٔ یک نظر مدرن جدید. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی در ارائه که نظر مدرن جدید باید به آن اضافه شود. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکل روی اسلاید که نظر مدرن جدید به آن مرتبط است. |
| position | java.awt.geom.Point2D.Float | موقعیت روی اسلاید که نظر مدرن جدید به آن اضافه می‌شود. |
| creationTime | java.util.Date | زمان ایجاد نظر مدرن. |

**بازگشت:**
[IModernComment](../../com.aspose.slides/imoderncomment) - نظر مدرن وارد‌شده.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

آرایه‌ای شامل تمام نظرات را ایجاد و باز می‌گرداند.

**بازگشت:**
com.aspose.slides.IComment[] - آرایه‌ای از [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

آرایه‌ای شامل تمام نظرات از بازهٔ مشخص‌شده را ایجاد و باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | اندیس اولین نظری که باید برگردانده شود. |
| count | int | تعداد نظراتی که باید برگردانده شود. |

**بازگشت:**
com.aspose.slides.IComment[] - آرایه‌ای از [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در اندیس مشخص‌شده در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر‌محور عنصری که باید حذف شود. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

اولین وقوع نظر مشخص‌شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | نظری که باید از مجموعه حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام نظرات را از مجموعه حذف می‌کند.