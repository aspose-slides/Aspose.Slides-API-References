---
title: add_audio_frame_embedded method
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
ينشئ إطار صوتي جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios.

### القيمة المرجعة

الـ [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | **io.RawIOBase** | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينها. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
ينشئ إطار صوتي جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

### القيمة المرجعة

الـ [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) | مثيل [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) من مجموعة Presentation.Audios. |



### انظر أيضًا
* الفئة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio)
* الفئة [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)