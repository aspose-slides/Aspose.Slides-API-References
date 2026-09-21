---
title: add_clone method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
یک نسخه از اسلاید طرح‌بندی مشخص را به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید اضافه شده.



```python
def add_clone(self, source_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید برای تکثیر. |

### توضیحات

1) طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی مرتبط خواهد شد.
            بنابراین این مشابه عملیات کپی/پیست با گزینه "Use Destination Theme" در PowerPoint است.
            2) معادل این روش، متد **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** است که با ویژگی [`IPresentation.layout_slides`](/slides/python-net/fa/aspose.slides/ipresentation/layout_slides) دسترسی پیدا می‌کند.



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)