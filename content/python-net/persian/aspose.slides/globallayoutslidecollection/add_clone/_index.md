---
title: add_clone method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند.

### Returns
اسلاید اضافه‌شده.

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید برای کلون. |

### Remarks
هنگام کلون‌کردن یک طرح‌بندی بین ارائه‌های مختلف، مستر طرح‌بندی نیز می‌تواند کلون شود تا قالب‌بندی منبع حفظ شود. یک رجیستری داخلی برای ردیابی مسترهای کلون‌شده به طور خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان اسلاید مستر جلوگیری کند. کلون‌کردن دستی اسلایدهای مستر نه جلوگیری می‌شود و نه ثبت می‌شود.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند.

### Returns
اسلاید اضافه‌شده.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید برای کلون. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | مستر اسلاید برای یک طرح‌بندی جدید. |

### Remarks
۱) طرح‌بندی جدید با مستر تعریف‌شده در ارائه مقصد پیوند خواهد شد. بنابراین این مشابه عملیات کپی/پیست با گزینه "Use Destination Theme" در PowerPoint است.  
۲) مشابه این متد، متد **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** است که از طریق ویژگی [`IMasterSlide.layout_slides`](/slides/python-net/fa/aspose.slides/imasterslide/layout_slides) دسترسی پیدا می‌کند.

### See Also
* class [`GlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)