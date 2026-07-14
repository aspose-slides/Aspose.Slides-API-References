---
title: CommentAuthorCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از نویسندگان نظرات.
type: docs
url: /fa/com.aspose.slides/commentauthorcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

نمایش‌دهندهٔ مجموعه‌ای از نویسندگان نظرات.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری را که واقعاً در مجموعه وجود دارند، دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد، دریافت می‌کند. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | نویسندهٔ جدیدی را در انتهای مجموعه اضافه می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام نویسندگان را ایجاد و برمی‌گرداند. |
| [findByName(String name)](#findByName-java.lang.String-) | نویسنده را در مجموعه با نام پیدا می‌کند. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | نویسنده را در مجموعه با نام و حروف اول پیدا می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نویسنده را در اندیس مشخص شدهٔ مجموعه حذف می‌کند. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | اولین رخداد نویسندهٔ مشخص شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نویسندگان را از یک مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک مرورگر (iterator) جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان (thread-safe) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد عناصری را که واقعاً در مجموعه وجود دارند، دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


عنصری را که در اندیس مشخص شده قرار دارد، دریافت می‌کند. فقط-خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


نویسندهٔ جدیدی را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسندهٔ جدید. |
| initials | java.lang.String | حروف اول نویسندهٔ جدید. |

**بازگشت:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - شیء جدید [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


یک آرایه شامل تمام نویسندگان را ایجاد و برمی‌گرداند.

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - آرایه‌ای از [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


نویسنده را در مجموعه با نام پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده برای جستجو. |

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


نویسنده را در مجموعه با نام و حروف اول پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده برای جستجو. |
| initials | java.lang.String | حروف اول نویسنده برای جستجو. |

**بازگشت:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


نویسنده را در اندیس مشخص شدهٔ مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفرمحور عنصری که باید حذف شود. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


اولین رخداد نویسندهٔ مشخص شده را در مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | نویسنده‌ای که باید از مجموعه حذف شود. |
### clear() {#clear--}
```
public final void clear()
```


تمام نویسندگان را از یک مجموعه حذف می‌کند.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


یک مرورگر (iterator) جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان (thread-safe) است یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object