---
title: TagCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر مجموعه‌ای از برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)
type: docs
url: /fa/com.aspose.slides/tagcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

نمایانگر مجموعه‌ای از برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعدادی از برچسب‌ها را در مجموعه برمی‌گرداند. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک برچسب جدید به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | شاخص صفر-پایهٔ کلید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [contains(String name)](#contains-java.lang.String-) | مشخص می‌کند که آیا مجموعه شامل نام خاصی است یا نه. |
| [removeAt(int index)](#removeAt-int-) | برچسب در اندیس مشخص‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام برچسب‌های مجموعه را حذف می‌کند. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | مقدار برچسب در اندیس مشخص‌شده را برمی‌گرداند. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | کلید برچسب در اندیس مشخص‌شده را برمی‌گرداند. |
| [getNamesOfTags()](#getNamesOfTags--) | نام‌های برچسب‌ها را برمی‌گرداند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را در آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن نسبت به چندنخی). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعدادی از برچسب‌ها را در مجموعه برمی‌گرداند. فقط-خواندنی int.

**بازگرداندن:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

یک برچسب جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برچسب. |
| value | java.lang.String | مقدار برچسب. |

**بازگرداندن:**
int - شاخص برچسب اضافه‌شده.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برچسب برای حذف. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

شاخص صفر-پایهٔ کلید مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برای یافتن در مجموعه. |

**بازگرداندن:**
int - شاخص صفر-پایهٔ کلید، اگر کلید در مجموعه یافت شود؛ در غیر این صورت، -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

مشخص می‌کند که آیا مجموعه شامل نام خاصی است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برای یافتن. |

**بازگرداندن:**
boolean - True اگر مجموعه شامل برچسبی با کلید مشخص باشد؛ در غیر این صورت، false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

برچسب در اندیس مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-پایهٔ برچسب برای حذف. |
### clear() {#clear--}
```
public final void clear()
```

تمام برچسب‌های مجموعه را حذف می‌کند.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

مقدار برچسب در اندیس مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص برچسب برای برگرداندن. |

**بازگرداندن:**
java.lang.String - مقدار برچسب.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

کلید برچسب در اندیس مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص برچسب برای برگرداندن. |

**بازگرداندن:**
java.lang.String - کلید برچسب.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

نام‌های برچسب‌ها را برمی‌گرداند.

**بازگرداندن:**
java.lang.String[] - نام‌های برچسب‌ها.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |

**بازگرداندن:**
java.lang.String - مقدار برچسب.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را در آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه برای پر کردن. |
| index | int | موقعیت شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن نسبت به چندنخی). فقط-خواندنی boolean.

**بازگرداندن:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگرداندن:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

یک شمارشگر که در مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.