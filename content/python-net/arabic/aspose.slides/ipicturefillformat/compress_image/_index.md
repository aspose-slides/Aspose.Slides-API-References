---
title: compress_image method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضًا بحذف المناطق المقصوصة.

### الإرجاع

قيمة **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. ترجع **True** إذا تم تغيير حجم الصورة أو قصها، وإلا **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | إذا كان true، فإن الطريقة ستحذف المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression) | الدقة الهدف للضغط، محددة كقيمة من تعداد [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression). |

### ملاحظات

تُغيّر هذه الطريقة حجم الصورة ودقتها مشابهًا لميزة PowerPoint "Picture Format -> Compress Pictures".

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح عندما لا تكون الدقة قيمة صالحة. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضًا بحذف المناطق المقصوصة.

### الإرجاع

قيمة **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. ترجع **True** إذا تم تغيير حجم الصورة أو قصها، وإلا **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | إذا كان true، فإن الطريقة ستحذف المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | **float** | الدقة الهدف بوحدة DPI. يجب أن تكون هذه القيمة موجبة وتحدد كيفية تغيير حجم الصورة. |

### ملاحظات

تُغيّر هذه الطريقة حجم الصورة ودقتها مشابهًا لميزة PowerPoint "Picture Format -> Compress Pictures".

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح عندما لا تكون الدقة قيمة موجبة. |



### انظر أيضًا
* فئة [`IPictureFillFormat`](/slides/python-net/ar/aspose.slides/ipicturefillformat)
* تعداد [`PicturesCompression`](/slides/python-net/ar/aspose.slides.export/picturescompression)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)