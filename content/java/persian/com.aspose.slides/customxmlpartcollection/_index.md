---
title: CustomXmlPartCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ مجموعه‌ای از قسمت‌های XML سفارشی.
type: docs
url: /fa/com.aspose.slides/customxmlpartcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

نماینده مجموعه‌ای از قسمت‌های xml سفارشی است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [size()](#size--) | Returns count of custom xml parts in the collection. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


عنصری که در اندیس مشخص‌شده قرار دارد را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا برای عنصر مورد نظر. |

**مقدار بازگشتی:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - عنصر در اندیس مشخص‌شده.
### size() {#size--}
```
public final int size()
```


تعداد قسمت‌های xml سفارشی در مجموعه را برمی‌گرداند. int فقط-خواندنی.

**مقدار بازگشتی:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlString | java.lang.String | رشته xml بخش جدید که باید اضافه شود. |

**مقدار بازگشتی:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجادشده.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlData | byte[] | داده‌های xml بخش جدید که باید اضافه شود. |

**مقدار بازگشتی:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجادشده.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


یک قسمت xml سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputStream | java.io.InputStream | جریان ورودی حاوی داده‌های xml بخش جدید که باید اضافه شود. |

**مقدار بازگشتی:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - قسمت xml سفارشی ایجادشده.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


قسمت xml سفارشی در اندیس مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا برای عنصری که باید حذف شود. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | قسمت xml سفارشی که باید حذف شود. |

**مقدار بازگشتی:**
boolean - true if item is successfully removed; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```


تمام آیتم‌ها را از مجموعه حذف می‌کند.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه‌ای که باید به آن کپی شود. |
| index | int | اندیسی که کپی از آن شروع می‌شود. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه هماهنگ (thread-safe) است یا نه. boolean فقط-خواندنی.

**مقدار بازگشتی:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


یک ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط-خواندنی.

**مقدار بازگشتی:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


یک متمم (enumerator) را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را برمی‌گرداند. IDOMObject فقط-خواندنی.

**مقدار بازگشتی:**
com.aspose.slides.IDOMObject