---
title: add_audio_frame_embedded method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

### بازگشت

[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) تازه ایجاد شده.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | فریم صوتی جدید در مختصات x، بر حسب پوینت. |
| y | **float** | فریم صوتی جدید در مختصات y، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینٹ. |
| audio_stream | **io.RawIOBase** | جریان ورودی حاوی داده‌های صوتی WAV برای جاسازی. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
یک فریم صوتی جدید ایجاد می‌کند و آن را با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) تازه ایجاد شده.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | فریم صوتی جدید در مختصات x، بر حسب پوینت. |
| y | **float** | فریم صوتی جدید در مختصات y، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینت. |
| audio | [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) | یک نمونهٔ [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) از مجموعهٔ Presentation.Audios. |



### موارد مرتبط
* کلاس [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio)
* کلاس [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)