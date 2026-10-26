---
title: remove method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
حذف یک لایه از مجموعه.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | لایه اسلایدی که باید از مجموعه حذف شود. |

### Remarks

1) برای جلوگیری از پرتاب استثنای PptxEditException قبل از آن، ویژگی HasDependingSlides لایه را بررسی کنید.
2) می‌توانید از متد [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) نیز برای ساده‌سازی کد استفاده کنید.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که لایه در ارائه استفاده شده باشد (ویژگی HasDependingSlides آن درست باشد) پرتاب می‌شود. |

### See Also
* کلاس [`GlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/globallayoutslidecollection)
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)