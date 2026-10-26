---
title: CustomXmlPartCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ مجموعه‌ای از قسمت‌های xml سفارشی.
type: docs
url: /fa/com.aspose.slides/customxmlpartcollection/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

نمایندهٔ مجموعه‌ای از قسمت‌های xml سفارشی.

## روش‌ها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده قرار دارد برمی‌گرداند. |
| [size()](#size--) | تعداد قسمت‌های xml سفارشی در مجموعه را برمی‌گرداند. |
| [add(String xmlString)](#add-java.lang.String-) | یک قسمت xml سفارشی جدید اضافه می‌کند. |
| [add(byte[] xmlData)](#add-byte---) | یک قسمت xml سفارشی جدید اضافه می‌کند. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | یک قسمت xml سفارشی جدید اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | قسمت xml سفارشی را در ایندکس مشخص شده حذف می‌کند. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | اولین وقوع یک شیء خاص را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام آیتم‌ها را از مجموعه حذف می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | در آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (Thread-Safe). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه مرور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

عنصری را که در ایندکس مشخص شده قرار دارد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفرمبنی عنصری که باید دریافت شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - عنصری که در ایندکس مشخص شده قرار دارد.

### size() {#size--}
```
public final int size()
```

تعداد قسمت‌های xml سفارشی در مجموعه را برمی‌گرداند. int فقط‌خواندنی.

**بازگشت:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlString | java.lang.String | رشتهٔ xml قسمت جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجاد شده.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlData | byte[] | دادهٔ xml قسمت جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجاد شده.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputStream | java.io.InputStream | ورودی stream حاوی دادهٔ xml قسمت جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجاد شده.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

قسمت xml سفارشی را در ایندکس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفرمبنی عنصری که باید حذف شود. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

اولین وقوع یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | قسمت xml سفارشی که باید حذف شود. |

**بازگشت:**
boolean - true اگر مورد با موفقیت حذف شود؛ در غیر این صورت false.

### clear() {#clear--}
```
public final void clear()
```

تمام آیتم‌ها را از مجموعه حذف می‌کند.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

در آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه‌ای که باید کپی شود. |
| index | int | اندیسی که کپی از آن شروع می‌شود. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (Thread-Safe). بولی فقط‌خواندنی.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط‌خواندنی.

**بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

یک شمارنده که از طریق مجموعه مرور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - یک IGenericEnumerator که می‌تواند برای مرور مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

یک java iterator برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - یک java.util.Iterator برای کل مجموعه.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. IDOMObject فقط‌خواندنی.

**بازگشت:**
com.aspose.slides.IDOMObject