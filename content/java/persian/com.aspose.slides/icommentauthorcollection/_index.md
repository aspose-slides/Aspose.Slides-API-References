---
title: ICommentAuthorCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از نویسندگان نظرات.
type: docs
url: /fa/com.aspose.slides/icommentauthorcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

نمایانگر مجموعه‌ای از نویسندگان نظرات.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | نویسنده جدید را در انتهای مجموعه اضافه می‌کند. |
| [toArray()](#toArray--) | آرایه‌ای شامل تمام نویسندگان را ایجاد و برمی‌گرداند. |
| [findByName(String name)](#findByName-java.lang.String-) | نویسنده را در مجموعه بر اساس نام پیدا می‌کند. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | نویسنده را در مجموعه بر اساس نام و حروف اولیه پیدا می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نویسنده موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | اولین رخداد نویسنده مشخص‌شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نویسندگان را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. فقط‌خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


نویسنده جدید را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده جدید. |
| initials | java.lang.String | حروف اولیه نویسنده جدید. |

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - شیء جدید [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


آرایه‌ای شامل تمام نویسندگان را ایجاد و برمی‌گرداند.

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - آرایه‌ای از [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


نویسنده را در مجموعه بر اساس نام پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده‌ای که باید پیدا شود. |

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


نویسنده را در مجموعه بر اساس نام و حروف اولیه پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده‌ای که باید پیدا شود. |
| initials | java.lang.String | حروف اولیه نویسنده‌ای که باید پیدا شود. |

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


نویسنده موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه عنصری که باید حذف شود. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


اولین رخداد نویسنده مشخص‌شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده‌ای که باید از مجموعه حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```


تمام نویسندگان را از مجموعه حذف می‌کند.