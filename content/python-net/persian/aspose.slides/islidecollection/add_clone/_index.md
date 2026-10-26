---
title: add_clone method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون کردن. |

### توضیحات

هنگام کلون کردن یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود.
            از رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌طور خودکار استفاده می‌شود تا از ایجاد
            کلون‌های متعدد از همان مستر اسلاید جلوگیری شود.
            کلون کردن دستی مستر اسلایدها نه جلوگیری می‌شود و نه ثبت می‌گردد.
            اگر به کنترل بیشتری بر فرآیند کلون نیاز دارید از
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** یا
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** برای کلون کردن اسلیدها،
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** یا
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** برای کلون کردن لایه‌ها و
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** برای کلون کردن مسترها.


## add_clone(self, source_slide, section) {#islide-isection}
یک کپی از اسلاید مشخص‌شده را به انتهای بخش مشخص‌شده اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, section):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون کردن. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | بخش برای یک اسلاید جدید. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
یک کپی از اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون کردن. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | لایه اسلاید برای یک اسلاید جدید. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
یک کپی از اسلاید منبع مشخص‌شده را به انتهای مجموعه اضافه می‌کند.
            طرح‌بندی مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود
            (طرح‌بندی مناسب همان طرح‌بندی است که همان Type یا Name را داشته باشد
            مانند طرح‌بندی اسلاید منبع). اگر طرح‌بندی مناسب وجود نداشته باشد،
            طرح‌بندی اسلاید منبع کلون خواهد شد (اگر allowCloneMissingLayout
            صحیح باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout
            نادرست باشد).

### بازگشت

اسلاید جدید.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای کلون کردن. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | مستر اسلاید برای یک اسلاید جدید. |
| allow_clone_missing_layout | **bool** | اگر طرح‌بندی مناسبی در مستر مشخص‌شده وجود نداشته باشد، طرح‌بندی اسلاید <br/><br/>            منبع کلون خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا <br/><br/>            PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که در مستر مشخص‌شده طرح‌بندی مناسبی وجود نداشته باشد و <br/>            allowCloneMissingLayout برابر false باشد، پرتاب می‌شود. |



### مراجع
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* کلاس [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)