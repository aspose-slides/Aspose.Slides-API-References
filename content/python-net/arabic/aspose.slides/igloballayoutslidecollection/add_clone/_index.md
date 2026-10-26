---
title: add_clone method
second_title: Aspose.Slides للغة Python عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
يضيف نسخة من شريحة التخطيط المحددة إلى العرض التقديمي.

### Returns
الشريحة المضافة.

```python
def add_clone(self, source_layout):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التي سيتم استنساخها. |

### Remarks
عند استنساخ تخطيط بين عروض تقديمية مختلفة يمكن استنساخ الـ master الخاص بالتخطيط أيضًا للحفاظ على تنسيق المصدر.
يتم استخدام السجل الداخلي لتتبع الـ masters المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من شريحة الـ master نفسها.
لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الـ master.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
يضيف نسخة من شريحة التخطيط المحددة إلى العرض التقديمي.

### Returns
الشريحة المضافة.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التي سيتم استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة master لتخطيط جديد. |

### Remarks
سيتم ربط التخطيط الجديد بالماستر المحدد في عرض تقديمي الوجهة.
وبالتالي فهذا مماثل لعملية النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.

### See Also
* فئة [`IGlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/igloballayoutslidecollection)
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)