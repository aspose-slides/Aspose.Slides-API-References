---
title: insert_audio_frame_embedded method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
یک فریم صوتی جدید با فایل WAV تعبیه‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌کند. صوت تعبیه‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

### بازگرداندن

مورد جدید ایجاد شده [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس مبتنی بر صفر که فریم صوتی در آن درج می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، به نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، به نقطه. |
| width | **float** | عرض فریم صوتی جدید، به نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقطه. |
| audio_stream | **io.RawIOBase** | یک جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
یک فریم صوتی جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده قرار می‌دهد با استفاده از یک شیء صوتی موجود در فهرست Presentation.Audios.

### بازگرداندن

مورد جدید ایجاد شده [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس مبتنی بر صفر که فریم صوتی در آن درج می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، به نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، به نقطه. |
| width | **float** | عرض فریم صوتی جدید، به نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقطه. |
| audio | [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) | نمونه‌ای از [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) از مجموعه Presentation.Audios برای جاسازی. |



### مرتبط
* کلاس [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio)
* کلاس [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)