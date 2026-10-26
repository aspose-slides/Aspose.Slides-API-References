---
title: TagCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)
type: docs
url: /fa/com.aspose.slides/tagcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

نمایش‌دهندهٔ مجموعهٔ برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)

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
| [size()](#size--) | تعداد برچسب‌ها را در مجموعه برمی‌گرداند. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک برچسب جدید به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | اندیس صفر-پایهٔ کلید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [contains(String name)](#contains-java.lang.String-) | تعیین می‌کند آیا مجموعه شامل نام خاصی است یا خیر. |
| [removeAt(int index)](#removeAt-int-) | برچسب در اندیس مشخص‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام برچسب‌ها را از مجموعه حذف می‌کند. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | مقدار برچسب در اندیس مشخص‌شده را برمی‌گرداند. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | کلید برچسب در اندیس مشخص‌شده را برمی‌گرداند. |
| [getNamesOfTags()](#getNamesOfTags--) | نام‌های برچسب‌ها را برمی‌گرداند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهندهٔ این که دسترسی به مجموعه همگام‌سازی شده است (Thread-safe) را برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که مجموعه را پیمایش می‌کند برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد برچسب‌ها را در مجموعه برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


یک برچسب جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام برچسب. |
| value | java.lang.String | مقدار برچسب. |

**بازگشت:**
int - اندیس برچسب اضافه‌شده.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام برچسب برای حذف. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


اندیس صفر-پایهٔ کلید مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | نام مورد جستجو در مجموعه. |

**بازگشت:**
int - اندیس صفر-پایهٔ کلید؛ اگر یافت نشد مقدار -1 برگردانده می‌شود.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


تعیین می‌کند آیا مجموعه شامل نام خاصی است یا خیر.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | کلید مورد جستجو. |

**بازگشت:**
boolean - True اگر مجموعه شامل برچسبی با کلید مشخص‌شده باشد؛ در غیر این صورت false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


برچسب در اندیس مشخص‌شده را حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایهٔ برچسب برای حذف. |
### clear() {#clear--}
```
public final void clear()
```


تمام برچسب‌ها را از مجموعه حذف می‌کند.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


مقدار یک برچسب را در اندیس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس برچسب برای برگرداندن. |

**بازگشت:**
java.lang.String - مقدار برچسب.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


کلید یک برچسب را در اندیس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس برچسب برای برگرداندن. |

**بازگشت:**
java.lang.String - کلید برچسب.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


نام‌های برچسب‌ها را برمی‌گرداند.

**بازگشت:**
java.lang.String[] - نام‌های برچسب‌ها.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |

**بازگشت:**
java.lang.String - مقدار برچسب.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | موقعیت شروع در آرایهٔ هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (Thread-safe). فقط-خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


یک enumerator که مجموعه را پیمایش می‌کند برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator برای پیمایش مجموعه.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator برای کل مجموعه.