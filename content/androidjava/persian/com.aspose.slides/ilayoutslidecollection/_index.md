---
title: ILayoutSlideCollection
second_title: Aspose.Slides برای Android از طریق API مرجع جاوا
description: یک کلاس پایه برای مجموعه‌ای از اسلایدهای طرح‌بندی را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ilayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

یک کلاس پایه برای مجموعه‌ای از اسلایدهای طرح‌بندی را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | اسلاید طرح‌بندی را بر اساس اندیس برمی‌گرداند. |
| [getByType(byte type)](#getByType-byte-) | اولین اسلاید طرح‌بندی از نوع مشخص‌شده را برمی‌گرداند. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | یک طرح‌بندی را از مجموعه حذف می‌کند. |
| [removeUnused()](#removeUnused--) | اسلایدهای طرح‌بندی استفاده‌نشده (اسلایدهای طرح‌بندی که HasDependingSlides آنها false است) را حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

اسلاید طرح‌بندی را بر اساس اندیس برمی‌گرداند. فقط‌خواندنی [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

اولین اسلاید طرح‌بندی از نوع مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | byte | یک نوع از اسلاید طرح‌بندی برای یافتن. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) با نوع مشخص‌شده یا null اگر هیچ طرحی یافت نشود.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

یک طرح‌بندی را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید طرح‌بندی که باید از مجموعه حذف شود.

--------------------

1) برای جلوگیری از پرتاب PptxEditException قبل از آن ویژگی HasDependingSlides طرح‌بندی را بررسی کنید. 2) همچنین می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) برای ساده‌سازی کد استفاده کنید. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

اسلایدهای طرح‌بندی استفاده‌نشده (اسلایدهای طرح‌بندی که HasDependingSlides آنها false است) را حذف می‌کند.