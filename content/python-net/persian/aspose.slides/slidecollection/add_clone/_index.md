---
title: add_clone method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
یک کپی از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون. |

### توضیحات

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید ممکن است نیز کلون شود.
            رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا جلوگیری از ایجاد
            کلون‌های متعدد از همان مستر اسلاید شود.
            کلون‌کردن دستی مستر اسلاید‌ها نه جلوگیری می‌شود و نه ثبت می‌گردد.
            اگر به کنترل بیشتر بر فرآیند کلون نیاز دارید از
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** یا
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** برای کلون کردن اسلایدها،
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** یا
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** برای کلون کردن لایه‌ها و
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** برای کلون کردن مسترها.



## add_clone(self, source_slide, section) {#islide-isection}
یک کپی از اسلاید مشخص شده را به انتهای بخش مشخص شده اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, section):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | بخش برای اسلاید جدید. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) |  |



## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
یک کپی از اسلاید مشخص شده را به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید لایه برای اسلاید جدید. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
یک کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند.
            لایه مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود
            (لایه مناسب، لایه‌ای است که نوع یا نام آن برابر با لایه اسلاید منبع باشد). اگر لایه مناسب وجود نداشته باشد،
            لایه اسلاید منبع کلون خواهد شد (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout غلط باشد).

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allow_clone_missing_layout | **bool** | اگر لایه مناسب در مستر مشخص‌شده وجود نداشته باشد، لایه اسلاید <br/><br/>            منبع کلون خواهد شد (اگر allowCloneMissingLayout درست باشد) یا <br/><br/>            PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout غلط باشد). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که لایه مناسب در مستر مشخص‌شده وجود نداشته باشد و <br/>            allowCloneMissingLayout غلط باشد پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* کلاس [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* کلاس [`SlideCollection`](/slides/python-net/fa/aspose.slides/slidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)