---
title: remove method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
لایه‌ای را از مجموعه حذف می‌کند.


```python
def remove(self, value):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | لایه اسلاید را که باید از مجموعه حذف شود. |

### توضیحات

1) برای جلوگیری از پرتاب PptxEditException، قبل از آن ویژگی HasDependingSlides layout را بررسی کنید.
2) می‌توانید از [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) نیز برای ساده‌سازی کد استفاده کنید.

### استثناها

| استثنا | توضیحات |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که لایه در ارائه استفاده شود (ویژگی HasDependingSlides آن true باشد) پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`LayoutSlideCollection`](/slides/python-net/fa/aspose.slides/layoutslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)