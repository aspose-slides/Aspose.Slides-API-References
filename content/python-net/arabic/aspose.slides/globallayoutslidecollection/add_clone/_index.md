---
title: add_clone method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

### القيمة المرجعة

الشريحة المضافة.



```python
def add_clone(self, source_layout):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |

### ملاحظات

عند استنساخ تخطيط بين عروض تقديمية مختلفة يمكن استنساخ ماستر التخطيط أيضًا
            للحفاظ على تنسيق المصدر.
            يتم استخدام سجل داخلي لتتبع الماسترات المستنسخة تلقائيًا لمنع إنشاء
            نسخ متعددة من ماستر الشريحة نفسه.
            لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر.



## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

### القيمة المرجعة

الشريحة المضافة.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة الماستر لتخطيط جديد. |

### ملاحظات

1) سيتم ربط التخطيط الجديد بالماستر المحدد في العرض التقديمي الهدف.
            لذا فإن هذا يُعادل النسخ/اللصق مع خيار "استخدام سمة الوجهة" في PowerPoint.
2) مماثل لهذا الأسلوب هو الأسلوب **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            يُستَخدم عبر خاصية [`IMasterSlide.layout_slides`](/slides/python-net/ar/aspose.slides/imasterslide/layout_slides).



### انظر أيضًا
* الفئة [`GlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/globallayoutslidecollection)
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)