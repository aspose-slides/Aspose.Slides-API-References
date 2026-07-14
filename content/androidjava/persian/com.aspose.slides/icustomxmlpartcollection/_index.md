---
title: ICustomXmlPartCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از بخش‌های xml سفارشی.
type: docs
url: /fa/com.aspose.slides/icustomxmlpartcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

نمایشگر مجموعه‌ای از بخش‌های xml سفارشی.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص شده را برمی‌گرداند. |
| [add(byte[] xmlData)](#add-byte---) | قسمت xml سفارشی جدیدی را اضافه می‌کند. |
| [add(String xmlString)](#add-java.lang.String-) | قسمت xml سفارشی جدیدی را اضافه می‌کند. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | قسمت xml سفارشی جدیدی را اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | بخش xml سفارشی را در اندیس مشخص شده حذف می‌کند. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام آیتم‌ها را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


عنصر موجود در اندیس مشخص شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا برای عنصری که باید دریافت شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - عنصر موجود در اندیس مشخص شده.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


قسمت xml سفارشی جدیدی را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlData | byte[] | داده‌های xml بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش xml سفارشی ساخته‌شده.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


قسمت xml سفارشی جدیدی را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlString | java.lang.String | رشته xml بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش xml سفارشی ساخته‌شده.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


قسمت xml سفارشی جدیدی را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputStream | java.io.InputStream | جریان ورودی با داده‌های xml بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش xml سفارشی ساخته‌شده.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


بخش xml سفارشی را در اندیس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا برای عنصری که باید حذف شود. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | بخش xml سفارشی برای حذف. |

**بازگشت:**
boolean - true اگر مورد با موفقیت حذف شود؛ در غیر این صورت false.
### clear() {#clear--}
```
public abstract void clear()
```


تمام آیتم‌ها را از مجموعه حذف می‌کند.