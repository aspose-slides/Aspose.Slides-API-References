---
title: ILayoutSlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک کلاس پایه برای مجموعه‌ای از اسلایدهای طرح‌بندی است.
type: docs
url: /fa/com.aspose.slides/ilayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

نمایانگر یک کلاس پایه برای مجموعه‌ای از اسلایدهای طرح‌بندی است.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | اسلاید طرح‌بندی را بر اساس اندیس برمی‌گرداند. |
| [getByType(byte type)](#getByType-byte-) | اولین اسلاید طرح‌بندی از نوع 지정‌شده را برمی‌گرداند. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | یک طرح‌بندی را از مجموعه حذف می‌کند. |
| [removeUnused()](#removeUnused--) | اسلایدهای طرح‌بندی استفاده‌نشده (اسلایدهایی که HasDependingSlides آن‌ها false است) را حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


اسلاید طرح‌بندی را بر اساس اندیس برمی‌گرداند. فقط خواندنی [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


اولین اسلاید طرح‌بندی از نوع مشخص‌شده را برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | نوع اسلاید طرح‌بندی که باید پیدا شود. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) با نوع مشخص‌شده یا null اگر هیچ طرح‌بندی یافت نشود.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


یک طرح‌بندی را از مجموعه حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید طرح‌بندی که باید از مجموعه حذف شود.

--------------------

1) برای جلوگیری از پرتاب PptxEditException، پیش از آن ویژگی HasDependingSlides طرح‌بندی را بررسی کنید. 2) همچنین می‌توانید از روش [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) برای ساده‌سازی کد استفاده کنید. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


اسلایدهای طرح‌بندی استفاده‌نشده (اسلایدهایی که HasDependingSlides آن‌ها false است) را حذف می‌کند.