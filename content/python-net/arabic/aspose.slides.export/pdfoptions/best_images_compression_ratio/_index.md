---
title: best_images_compression_ratio property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio الخاصية
Indicates if the most effective compression (instead of the default one) for each image must be selected 
            تلقائياً. If set to **bool**.true, for every image in presentation the most appropriate compression 
            algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. 
            Best image compression ratio selection is computationally expensive and takes 
            an additional amount of RAM, and this option is **bool**.false بشكل افتراضي.


### ملاحظات

القيمة الافتراضية هي **bool**.false.

### التعريف:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### انظر أيضًا
* الفئة [`PdfOptions`](/slides/python-net/ar/aspose.slides.export/pdfoptions)
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)