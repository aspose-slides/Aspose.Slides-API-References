---
title: add_audio_frame_embedded method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
يقوم بإنشاء إطار صوتي جديد يحتوي على ملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios.

### إرجاع

العنصر المُنشأ حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



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
يقوم بإنشاء إطار صوتي جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

### إرجاع

العنصر المُنشأ حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



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
| audio | [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) | مثال [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) من مجموعة Presentation.Audios. |



### انظر أيضًا
* فئة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio)
* فئة [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe)
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)