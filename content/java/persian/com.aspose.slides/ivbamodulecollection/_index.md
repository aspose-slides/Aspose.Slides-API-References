---
title: IVbaModuleCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایشگر یک مجموعه از ماژول‌های پروژه VBA.
type: docs
url: /fa/com.aspose.slides/ivbamodulecollection/
---
**همه رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

نمایشگر یک مجموعه از ماژول‌های پروژه VBA.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده قرار دارد بر می‌گرداند. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | یک ماژول خالی جدید به پروژه VBA اضافه می‌کند. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


عنصری را که در ایندکس مشخص شده قرار دارد بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
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

**بازگشت:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - ماژول اضافه شده.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | ماژولی که باید از مجموعه حذف شود. |