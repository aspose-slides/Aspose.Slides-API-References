---
title: ICellCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایش‌دهنده‌ای برای مجموعه‌ای از سلول‌ها.
type: docs
url: /fa/com.aspose.slides/icellcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

نمایش‌دهنده‌ای برای مجموعه‌ای از سلول‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک سلول را بر اساس موقعیت‌اش باز می‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

یک سلول را بر اساس موقعیت‌اش باز می‌گرداند. فقط-خواندنی [ICell](../../com.aspose.slides/icell).

--------------------

یک شیء CellEx می‌تواند برای چندین ایندکس بازگردانده شود در صورتی که سلول ادغام شده باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**مقدار بازگشتی:**
[ICell](../../com.aspose.slides/icell)