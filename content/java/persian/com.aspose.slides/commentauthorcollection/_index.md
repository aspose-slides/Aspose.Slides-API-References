---
title: CommentAuthorCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از نویسندگان نظرات.
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

نمایانندهٔ مجموعه‌ای از نویسندگان نظرات.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | یک نویسنده جدید را در انتهای مجموعه اضافه می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام نویسندگان ایجاد و برمی‌گرداند. |
| [findByName(String name)](#findByName-java.lang.String-) | نویسنده را در یک مجموعه بر اساس نام پیدا می‌کند. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | نویسنده را در یک مجموعه بر اساس نام و حروف اولیه پیدا می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نویسنده موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | اولین رخداد نویسندهٔ مشخص‌شده را در مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام نویسندگان را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | یک مقدار برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن در برابر نخ). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. فقط-خواندنی int.

**باز می‌گرداند:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. فقط-خواندنی [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


یک نویسندهٔ جدید را در انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام یک نویسندهٔ جدید. |
| initials | java.lang.String | حروف اولیهٔ یک نویسندهٔ جدید. |

**باز می‌گرداند:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - شیء جدید [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


یک آرایه شامل تمام نویسندگان ایجاد و برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.slides.ICommentAuthor[] - آرایه‌ای از [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


نویسنده را در یک مجموعه بر اساس نام پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده‌ای که باید پیدا شود. |

**باز می‌گرداند:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


نویسنده را در یک مجموعه بر اساس نام و حروف اولیه پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام نویسنده‌ای که باید پیدا شود. |
| initials | java.lang.String | حروف اولیهٔ نویسنده‌ای که باید پیدا شود. |

**باز می‌گرداند:**
com.aspose.slides.ICommentAuthor[] - نویسنده یا null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


نویسنده موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-محور عنصری که باید حذف شود. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


اولین رخداد نویسندهٔ مشخص‌شده را در یک مجموعه حذف می‌کند.

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


یک شمارنده برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


یک مقدار برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن در برابر نخ). فقط-خواندنی boolean.

**باز می‌گرداند:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**باز می‌گرداند:**
java.lang.Object