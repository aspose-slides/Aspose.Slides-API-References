---
title: ICellCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از سلول‌ها.
type: docs
url: /fa/com.aspose.slides/icellcollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

نمایش یک مجموعه از سلول‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک سلول را بر اساس موقعیت آن برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

یک سلول را بر اساس موقعیت آن برمی‌گرداند. فقط خواندنی [ICell](../../com.aspose.slides/icell).

--------------------

یک شیء CellEx می‌تواند برای چندین شاخص برگردانده شود در صورتی که سلول ترکیب شده باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICell](../../com.aspose.slides/icell)