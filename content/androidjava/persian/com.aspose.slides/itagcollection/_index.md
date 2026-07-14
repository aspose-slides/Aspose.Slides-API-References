---
title: ITagCollection
second_title: Aspose.Slides برای Android – مرجع API جاوا
description: نمایش‌دهنده مجموعه‌ای از برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)
type: docs
url: /fa/com.aspose.slides/itagcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

نمایش‌دهنده مجموعه برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)
## روش‌ها

| متد | توضیح |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک برچسب جدید به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | برچسبی با نام مشخص را از مجموعه حذف می‌کند. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | اندیس صفر-محور کلید مشخص‌شده در مجموعه را بر می‌گرداند. |
| [contains(String name)](#contains-java.lang.String-) | تعیین می‌کند که آیا مجموعه شامل نام خاصی است یا خیر. |
| [removeAt(int index)](#removeAt-int-) | برچسب در اندیس مشخص‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام برچسب‌ها را از مجموعه حذف می‌کند. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | مقدار برچسب در اندیس مشخص‌شده را بر می‌گرداند. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | کلید برچسب در اندیس مشخص‌شده را بر می‌گرداند. |
| [getNamesOfTags()](#getNamesOfTags--) | نام‌های برچسب‌ها را بر می‌گرداند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | کلید و مقدار یک برچسب را بر می‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | کلید و مقدار یک برچسب را بر می‌گرداند یا تنظیم می‌کند. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

یک برچسب جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برچسب. |
| value | java.lang.String | مقدار برچسب. |

**بازگشت:**
int - اندیس برچسب افزوده‌شده.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

برچسبی با نام مشخص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برچسب برای حذف. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

اندیس صفر-محور کلید مشخص‌شده در مجموعه را بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برای یافتن در مجموعه. |

**بازگشت:**
int - اندیس صفر-محور کلید، اگر کلید در مجموعه یافت شود؛ در غیر اینصورت -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

تعیین می‌کند که آیا مجموعه شامل برچسبی با کلید مشخص است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برای یافتن. |

**بازگشت:**
boolean - اگر مجموعه شامل برچسبی با کلید مشخص باشد True؛ در غیر اینصورت false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

برچسب در اندیس مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-محور برچسب برای حذف. |
### clear() {#clear--}
```
public abstract void clear()
```

تمام برچسب‌ها را از مجموعه حذف می‌کند.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

مقدار برچسب در اندیس مشخص‌شده را بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برچسب برای بازگرداندن. |

**بازگشت:**
java.lang.String - مقدار برچسب.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

کلید برچسب در اندیس مشخص‌شده را بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برچسب برای بازگرداندن. |

**بازگشت:**
java.lang.String - کلید برچسب.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

نام‌های برچسب‌ها را بر می‌گرداند.

**بازگشت:**
java.lang.String[] - نام‌های برچسب.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

کلید و مقدار یک برچسب را بر می‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |

**بازگشت:**
java.lang.String - مقدار برچسب.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

کلید و مقدار یک برچسب را بر می‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |
| value | java.lang.String |  |