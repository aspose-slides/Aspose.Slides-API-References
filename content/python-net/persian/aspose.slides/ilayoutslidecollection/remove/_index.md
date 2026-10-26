---
title: remove method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
طرح یک لایه از مجموعه را حذف می‌کند.


```python
def remove(self, value):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید لایه برای حذف از مجموعه. |

### توضیحات

1) برای جلوگیری از پرتاب PptxEditException قبل از آن خصوصیت HasDependingSlides لایه را بررسی کنید.
            2) همچنین می‌توانید از متد [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) برای ساده‌سازی کد استفاده کنید.

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر لایه در ارائه استفاده شود (خصوصیت HasDependingSlides آن true باشد) پرتاب می‌شود. |



### مراجع
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`ILayoutSlideCollection`](/slides/python-net/fa/aspose.slides/ilayoutslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)