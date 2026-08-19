---
title: IControlPropertiesCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: یک مجموعه از کنترل‌های ActiveX.
type: docs
url: /fa/com.aspose.slides/icontrolpropertiescollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

یک مجموعه از کنترل‌های ActiveX.

## متدها

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک ویژگی را به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | ویژگی‌ای با نام مشخص حذف می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getNamesOfProperties()](#getNamesOfProperties--) | تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. |
| [clear()](#clear--) | تمام ویژگی‌ها را حذف می‌کند. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**
int

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

یک ویژگی را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String | مقدار ویژگی. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

ویژگی‌ای با نام مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی برای حذف. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. فقط‌خواندنی [IGenericCollection](../../com.aspose.slides/igenericcollection).

**بازگرداندن:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public abstract void clear()
```

تمام ویژگی‌ها را حذف می‌کند.