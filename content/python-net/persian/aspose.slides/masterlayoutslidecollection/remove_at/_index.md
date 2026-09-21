---
title: remove_at method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
عنصری را که در اندیس مشخص شده از مجموعه قرار دارد حذف می‌کند.

```python
def remove_at(self, index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایهٔ عنصری که باید حذف شود. |

### یادداشت‌ها

1) برای جلوگیری از پرتاب PptxEditException پیش از آن ویژگی HasDependingSlides از layout را بررسی کنید.  
2) می‌توانید از متد [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) نیز برای ساده‌سازی کد استفاده کنید.

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که layout در ارائه استفاده شود (ویژگی HasDependingSlides آن true است) پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)