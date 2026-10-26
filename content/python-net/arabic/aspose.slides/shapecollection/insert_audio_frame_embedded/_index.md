---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Creates a new audio frame with an embedded WAV file and inserts it into the shape
            collection at the specified index. The embedded audio is added to the Presentation.Audios
            collection.

### إرجاع

العنصر الذي تم إنشاؤه حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| معلمة | نوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي س لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي ص لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | **io.RawIOBase** | دفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Creates a new audio frame and inserts it into the shape collection at the specified index
            using an existing audio object from the Presentation.Audios list.

### إرجاع

العنصر الذي تم إنشاؤه حديثًا [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| معلمة | نوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي س لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي ص لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) | كائن [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio) من مجموعة Presentation.Audios لتضمينه. |



### انظر أيضًا
* فئة [`IAudio`](/slides/python-net/ar/aspose.slides/iaudio)
* فئة [`IAudioFrame`](/slides/python-net/ar/aspose.slides/iaudioframe)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)