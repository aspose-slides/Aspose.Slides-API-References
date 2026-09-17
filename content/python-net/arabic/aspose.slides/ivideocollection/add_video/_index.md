---
title: add_video method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
يضيف نسخة من ملف فيديو من عرض تقديمي آخر.

### الإرجاع
تم إضافة الفيديو.



```python
def add_video(self, video):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/ar/aspose.slides/ivideo) | فيديو المصدر. |


## add_video(self, video_data) {#bytes}
ينشئ ويضيف فيديو إلى عرض تقديمي من مصفوفة بايت.

### الإرجاع
تم إضافة الفيديو.



```python
def add_video(self, video_data):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| video_data | **bytes** | بايتات الفيديو. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ينشئ ويضيف فيديو إلى عرض تقديمي من تدفق.

### الإرجاع
تم إضافة [`IVideo`](/slides/python-net/ar/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | التدفق لإضافة ملف الفيديو منه. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior) | السلوك الذي سيُطبق على التدفق. |



### انظر أيضاً
* الفئة [`IVideo`](/slides/python-net/ar/aspose.slides/ivideo)
* الفئة [`IVideoCollection`](/slides/python-net/ar/aspose.slides/ivideocollection)
* التعداد [`LoadingStreamBehavior`](/slides/python-net/ar/aspose.slides/loadingstreambehavior)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)