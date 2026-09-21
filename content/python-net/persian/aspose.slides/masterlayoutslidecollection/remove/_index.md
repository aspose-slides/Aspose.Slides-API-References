---
title: remove method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
حذف یک طرح از مجموعه.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید طرح برای حذف از مجموعه. |

### توضیحات

1) برای جلوگیری از پرتاب PptxEditException، پیش از آن ویژگی HasDependingSlides طرح را بررسی کنید.  
2) می‌توانید از روش [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) نیز برای ساده‌سازی کد استفاده کنید.

### استثناها

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که طرح در ارائه استفاده شود پرتاب می‌شود (ویژگی HasDependingSlides آن صحیح است). |

### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)