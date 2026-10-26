---
title: ICustomXmlPartCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از بخش‌های XML سفارشی است.
type: docs
url: /fa/com.aspose.slides/icustomxmlpartcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

نمایانگر مجموعه‌ای از بخش‌های XML سفارشی است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری که در اندیس مشخص شده قرار دارد را برمی‌گرداند. |
| [add(byte[] xmlData)](#add-byte---) | یک بخش XML سفارشی جدید اضافه می‌کند. |
| [add(String xmlString)](#add-java.lang.String-) | یک بخش XML سفارشی جدید اضافه می‌کند. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | یک بخش XML سفارشی جدید اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | بخش XML سفارشی را در اندیس مشخص شده حذف می‌کند. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام موارد را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

عنصری که در اندیس مشخص شده قرار دارد را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-محور عنصری که می‌خواهید دریافت کنید. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - عنصری که در اندیس مشخص شده قرار دارد.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

یک بخش XML سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlData | byte[] | داده‌های XML بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش XML سفارشی ساخته شده.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

یک بخش XML سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlString | java.lang.String | رشته XML بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش XML سفارشی ساخته شده.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

یک بخش XML سفارشی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputStream | java.io.InputStream | جریان ورودی حاوی داده‌های XML بخش جدیدی که باید اضافه شود. |

**بازگشت:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - بخش XML سفارشی ساخته شده.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

بخش XML سفارشی را در اندیس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-محور عنصری که می‌خواهید حذف شود. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | بخش XML سفارشی برای حذف. |

**بازگشت:**
boolean - true اگر مورد با موفقیت حذف شود؛ در غیر این صورت false.
### clear() {#clear--}
```
public abstract void clear()
```

تمام موارد را از مجموعه حذف می‌کند.