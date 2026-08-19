---
title: ITagCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ مجموعهٔ برچسب‌ها به‌صورت جفت‌های رشته‌ای تعریف‌شده توسط کاربر
type: docs
url: /fa/com.aspose.slides/itagcollection/
---
**همه اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

نمایندهٔ مجموعهٔ برچسب‌ها (جفت‌های رشته‌ای تعریف‌شده توسط کاربر)
## متدها

| متد | توضیح |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک برچسب جدید به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | شاخص صفر مبنا از کلید مشخص‌شده در مجموعه را برمی‌گرداند. |
| [contains(String name)](#contains-java.lang.String-) | تعیین می‌کند که آیا مجموعه شامل نام خاصی است یا خیر. |
| [removeAt(int index)](#removeAt-int-) | برچسب در شاخص مشخص‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام برچسب‌ها را از مجموعه حذف می‌کند. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | مقدار یک برچسب در شاخص مشخص‌شده را برمی‌گرداند. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | کلید یک برچسب در شاخص مشخص‌شده را برمی‌گرداند. |
| [getNamesOfTags()](#getNamesOfTags--) | نام‌های برچسب‌ها را برمی‌گرداند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | یک جفت کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | یک جفت کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند. |
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
int - شاخص برچسب اضافه‌شده.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

برچسب با نام مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برچسب برای حذف. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

شاخص صفر مبنا از کلید مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام برای یافتن در مجموعه. |

**بازگشت:**
int - شاخص صفر مبنا از کلید، اگر کلید در مجموعه یافت شود؛ در غیر این صورت -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

تعیین می‌کند که آیا مجموعه شامل نام خاصی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برای یافتن. |

**بازگشت:**
boolean - True اگر مجموعه شامل یک برچسب با کلید مشخص‌شده باشد؛ در غیر این صورت, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

برچسب در شاخص مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا برچسب برای حذف. |
### clear() {#clear--}
```
public abstract void clear()
```

تمام برچسب‌ها را از مجموعه حذف می‌کند.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

مقدار یک برچسب در شاخص مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص برچسب برای برگردانده شدن. |

**بازگشت:**
java.lang.String - مقدار برچسب.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

کلید یک برچسب در شاخص مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص برچسب برای برگردانده شدن. |

**بازگشت:**
java.lang.String - کلید برچسب.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

نام‌های برچسب‌ها را برمی‌گرداند.

**بازگشت:**
java.lang.String[] - نام‌های برچسب‌ها.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

یک جفت کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

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

یک جفت کلید و مقدار یک برچسب را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | کلید برچسب. |
| value | java.lang.String |  |