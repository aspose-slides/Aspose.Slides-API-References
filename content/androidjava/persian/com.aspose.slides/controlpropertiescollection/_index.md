---
title: ControlPropertiesCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: مجموعه‌ای از ویژگی‌های AcitveX.
type: docs
url: /fa/com.aspose.slides/controlpropertiescollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

یک مجموعه از ویژگی‌های AcitveX.

## متدها

| متد | توضیح |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک ویژگی به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | یک ویژگی با نام مشخص حذف می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getNamesOfProperties()](#getNamesOfProperties--) | مجموعهٔ نام‌های ویژگی‌ها را برمی‌گرداند. |
| [clear()](#clear--) | تمام ویژگی‌ها را حذف می‌کند. |
| [getCount()](#getCount--) | تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

یک ویژگی به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String | مقدار ویژگی. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

یک ویژگی با نام مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی برای حذف. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |

**بازگرداندن:**
java.lang.String - ویژگی.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

مجموعهٔ نام‌های ویژگی‌ها را برمی‌گرداند. فقط-خواندنی [IGenericCollection](../../com.aspose.slides/igenericcollection).

**بازگرداندن:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

تمام ویژگی‌ها را حذف می‌کند.

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگرداندن:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

یک شمارنده که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - یک IGenericEnumerator که می‌تواند برای تکرار از طریق مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - یک java.util.Iterator برای کل مجموعه.