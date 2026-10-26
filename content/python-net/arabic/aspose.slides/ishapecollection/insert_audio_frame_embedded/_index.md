---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
يقوم بإنشاء إطار صوت جديد يحتوي على ملف WAV مضمّن ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يُضاف الصوت المضمّن إلى مجموعة Presentation.Audios.

### القيمة المرجعة

العنصر الذي تم إنشاؤه حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| معلمة | نوع | وصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي سيتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي X لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | العرض لإطار الصوت الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio_stream | **io.RawIOBase** | دفق إدخال يحتوي على بيانات صوتية بصيغة WAV لتضمينه. |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
يقوم بإنشاء إطار صوت جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

### القيمة المرجعة

العنصر الذي تم إنشاؤه حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| معلمة | نوع | وصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي سيتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي X لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | العرض لإطار الصوت الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio | [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) | مثال [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) من مجموعة Presentation.Audios لتضمينه. |

### انظر أيضًا
* الفئة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio)
* الفئة [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)