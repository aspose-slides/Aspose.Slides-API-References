---
title: add_clone method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
یک کپی از اسلاید چیدمان مشخص شده را به ارائه اضافه می‌کند.

### بازگشت

اسلاید اضافه شده.



```python
def add_clone(self, source_layout):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلایدی که باید شبیه‌سازی شود. |

### توضیحات

هنگام شبیه‌سازی یک چیدمان بین ارائه‌های مختلف، می‌تواند مستر چیدمان نیز شبیه‌سازی شود
            تا قالب‌بندی منبع حفظ شود.
            رجیستری داخلی برای پیگیری مسترهای شبیه‌سازی‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد
            کپی‌های متعدد از همان اسلاید مستر جلوگیری شود.
            شبیه‌سازی دستی اسلایدهای مستر هم جلوگیری نمی‌شود و هم ثبت نمی‌شود.



## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
یک کپی از اسلاید چیدمان مشخص شده را به ارائه اضافه می‌کند.

### بازگشت

اسلاید اضافه شده.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلایدی که باید شبیه‌سازی شود. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | اسلاید مستر برای یک چیدمان جدید. |

### توضیحات

چیدمان جدید با مستر تعریف‌شده در ارائه مقصد مرتبط می‌شود.
            بنابراین این عمل مشابه کپی/پیست با گزینه «استفاده از تم مقصد» در پاورپوینت است.



### مراجع
* کلاس [`IGlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/igloballayoutslidecollection)
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)