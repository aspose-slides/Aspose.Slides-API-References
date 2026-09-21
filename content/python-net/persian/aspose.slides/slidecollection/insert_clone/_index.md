---
title: insert_clone method
second_title: Aspose.Slides برای پایتون از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
یک نسخه از اسلاید مشخص شده را در موقعیت مشخصی از مجموعه وارد می‌کند.

### بازگشت

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای شبیه‌سازی. |

### توضیحات

در هنگام شبیه‌سازی یک اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند شبیه‌سازی شود.
            رجیستری داخلی برای ردیابی مسترهای شبیه‌سازی‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد شبیه‌سازی‌های متعدد از یک مستر اسلاید جلوگیری شود.
            شبیه‌سازی دستی مستر اسلایدها نه منع می‌شود و نه ثبت می‌گردد.
            اگر به کنترل بیشتری بر فرآیند شبیه‌سازی نیاز دارید، از
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** یا
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** برای شبیه‌سازی اسلایدها و
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** برای شبیه‌سازی مسترها استفاده کنید.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
یک نسخه از اسلاید مشخص شده را در موقعیت مشخصی از مجموعه وارد می‌کند.

### بازگشت

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای شبیه‌سازی. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | طرح اسلاید برای اسلاید جدید. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
یک نسخه از اسلاید منبع مشخص شده را در موقعیت مشخصی از مجموعه وارد می‌کند.
            طرح مناسب به‌صورت خودکار از مستر مشخص‌شده انتخاب می‌شود
            (طرح مناسب همان طرحی است که نوع یا نام آن با طرح اسلاید منبع یکسان باشد). اگر طرح مناسبی وجود نداشته باشد،
            طرح اسلاید منبع شبیه‌سازی می‌شود (اگر allowCloneMissingLayout درست باشد) یا PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد).

### بازگشت

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید برای شبیه‌سازی. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allow_clone_missing_layout | **bool** | اگر در مستر مشخص‌شده طرح مناسبی وجود نداشته باشد، طرح اسلاید <br/><br/>            منبع شبیه‌سازی می‌شود (اگر allowCloneMissingLayout درست باشد) یا <br/><br/>            PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout نادرست باشد). |

### استثناها

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر در مستر مشخص‌شده طرح مناسبی وجود نداشته باشد و <br/>            allowCloneMissingLayout نادرست باشد، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* کلاس [`SlideCollection`](/slides/python-net/fa/aspose.slides/slidecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)