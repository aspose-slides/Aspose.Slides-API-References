---
title: ICommentAuthorCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از نویسندگان نظرات است.
type: docs
url: /fa/com.aspose.slides/icommentauthorcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

نمایانگر یک مجموعه از نویسندگان نظرات است.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | نویسنده جدید را در انتهای مجموعه اضافه می‌کند. |
| [toArray()](#toArray--) | یک آرایه با تمام نویسندگان ایجاد و برمی‌گرداند. |
| [findByName(String name)](#findByName-java.lang.String-) | نویسنده را در مجموعه بر اساس نام پیدا می‌کند. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | نویسنده را در مجموعه بر اساس نام و حروف اولیه پیدا می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نویسنده را در ایندکس مشخص‌شده از مجموعه حذف می‌کند. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | اولین رخداد نویسندهٔ مشخص‌شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نویسندگان را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


عنصر را در ایندکس مشخص‌شده دریافت می‌کند. فقط-خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


نویسنده جدید را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسندهٔ جدید. |
| initials | java.lang.String | حروف اولیهٔ نویسندهٔ جدید. |

**بازگرداندن:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - شیء جدید [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


یک آرایه با تمام نویسندگان ایجاد و برمی‌گرداند.

**بازگرداندن:**
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

**بازگرداندن:**
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
| initials | java.lang.String | حروف اولیهٔ نویسنده‌ای که باید پیدا شود. |

**بازگرداندن:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


نویسنده را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا برای عنصری که باید حذف شود. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


اولین رخداد نویسندهٔ مشخص‌شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده‌ای که باید از مجموعه حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```


تمام نویسندگان را از مجموعه حذف می‌کند.