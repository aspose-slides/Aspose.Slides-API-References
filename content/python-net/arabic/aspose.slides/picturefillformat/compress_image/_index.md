---
title: compress_image method
second_title: مرجع API Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضاً بحذف المناطق المقصوصة.

### القيمة المرجعة

قيمة **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. تُعيد **True** إذا تم تعديل حجم الصورة أو قصها، وإلا تُعيد **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | إذا كان true، سيقوم الأسلوب بإزالة المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression) | الدقة المستهدفة للضغط، محددة كقيمة من تعداد [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression). |

### ملاحظات

هذا الأسلوب يغيّر حجم الصورة ودقتها مشابهًا لميزة PowerPoint "Picture Format -> Compress Pictures".

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق عندما تكون الدقة ليست قيمة صالحة. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
يضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضاً بحذف المناطق المقصوصة.

### القيمة المرجعة

قيمة **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. تُعيد **True** إذا تم تعديل حجم الصورة أو قصها، وإلا تُعيد **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | إذا كان true، سيقوم الأسلوب بإزالة المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | **float** | الدقة المستهدفة بوحدة DPI. يجب أن تكون هذه القيمة موجبة وتحدد كيفية تعديل حجم الصورة. |

### ملاحظات

هذا الأسلوب يغيّر حجم الصورة ودقتها مشابهًا لميزة PowerPoint "Picture Format -> Compress Pictures".

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق عندما تكون الدقة غير قيمة موجبة. |



### انظر أيضًا
* فئة [`PictureFillFormat`](/slides/python-net/ar/aspose.slides/picturefillformat)
* تعداد [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)