---
title: IVbaModuleCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از ماژول‌های پروژه VBA است.
type: docs
url: /fa/com.aspose.slides/ivbamodulecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

نمایانگر مجموعه‌ای از ماژول‌های پروژه VBA است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | یک ماژول خالی جدید به پروژه VBA اضافه می‌کند. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**برگشت:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

یک ماژول خالی جدید به پروژه VBA اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ماژول |

**برگشت:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - ماژول اضافه‌شده.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | ماژولی که می‌خواهید از مجموعه حذف کنید. |