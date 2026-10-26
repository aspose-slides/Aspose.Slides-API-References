---
title: add_clone method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
یک کپی از اسلاید چیدمان مشخص را به انتهای مجموعه اضافه می‌کند.

### بازگرداندن

اسلاید اضافه شده.



```python
def add_clone(self, source_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلایدی که باید کلون شود. |

### توضیحات

1) چیدمان جدید با اسلاید مستر والد برای این مجموعه اسلایدهای چیدمان لینک خواهد شد.
            بنابراین این معادل کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است.
            2) معادل این متد، متد **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            که با خصوصیت [`IPresentation.layout_slides`](/slides/python-net/fa/aspose.slides/ipresentation/layout_slides) دسترسی پیدا می‌شود.



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)