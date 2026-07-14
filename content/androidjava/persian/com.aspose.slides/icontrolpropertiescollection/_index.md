---
title: IControlPropertiesCollection
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: یک مجموعه از کنترل‌های ActiveX.
type: docs
url: /fa/com.aspose.slides/icontrolpropertiescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

مجموعه‌ای از کنترل‌های ActiveX.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک ویژگی را به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | یک ویژگی با نام مشخص را حذف می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getNamesOfProperties()](#getNamesOfProperties--) | تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. |
| [clear()](#clear--) | تمام ویژگی‌ها را حذف می‌کند. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**Returns:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


یک ویژگی را به مجموعه اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String | مقدار ویژگی. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


یک ویژگی با نام مشخص را حذف می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی برای حذف. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |

**Returns:**
java.lang.String - ویژگی.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


تعداد ویژگی‌ها در مجموعه را برمی‌گرداند. فقط-خواندنی [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


تمام ویژگی‌ها را حذف می‌کند.