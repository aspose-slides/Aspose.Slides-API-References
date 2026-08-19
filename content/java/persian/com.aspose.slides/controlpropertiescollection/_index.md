---
title: ControlPropertiesCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: مجموعه‌ای از ویژگی‌های AcitveX.
type: docs
url: /fa/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**  
ارث-بری:  
java.lang.Object

**All Implemented Interfaces:**  
تمام اینترفیس‌های پیاده‌سازی‌شده:  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

مجموعه‌ای از ویژگی‌های AcitveX.

## متدها

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | یک ویژگی را به مجموعه اضافه می‌کند. |
| [remove(String name)](#remove-java.lang.String-) | یک ویژگی را با نام مشخص حذف می‌کند. |
| [get_Item(String name)](#get-Item-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ویژگی را برمی‌گرداند یا تنظیم می‌کند. |
| [getNamesOfProperties()](#getNamesOfProperties--) | مجموعه‌ای از نام‌های ویژگی‌ها را برمی‌گرداند. |
| [clear()](#clear--) | تمام ویژگی‌ها را حذف می‌کند. |
| [getCount()](#getCount--) | تعداد ویژگی‌های موجود در مجموعه را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده ارائه می‌دهد که مجموعه را پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

یک ویژگی را به مجموعه اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String | مقدار ویژگی. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

یک ویژگی را با نام مشخص حذف می‌کند.

**Parameters:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی برای حذف. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**Parameters:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |

**Returns:**
java.lang.String - ویژگی.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

ویژگی را برمی‌گرداند یا تنظیم می‌کند.

**Parameters:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| name | java.lang.String | نام ویژگی. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

مجموعه‌ای از نام‌های ویژگی‌ها را برمی‌گرداند. فقط‌خواندنی [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
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

تعداد ویژگی‌های موجود در مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**Returns:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

یک شمارنده ارائه می‌دهد که مجموعه را پیمایش می‌کند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.