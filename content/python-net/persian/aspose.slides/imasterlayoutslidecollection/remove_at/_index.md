---
title: remove_at method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.

```python
def remove_at(self, index):
    ...
```

| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| index | **int** | ایندکس صفر-پایه عنصر برای حذف. |

### توضیحات

1) برای جلوگیری از پرتاب PptxEditException، قبل از آن ویژگی HasDependingSlides طرح را بررسی کنید.
            2) همچنین می‌توانید از روش [`ILayoutSlide.remove`](/slides/python-net/fa/aspose.slides/ilayoutslide/remove) برای ساده‌سازی کد استفاده کنید.

### استثناها

| استثنا | توضیحات |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر طرح در ارائه استفاده شود (ویژگی HasDependingSlides آن درست باشد) پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)