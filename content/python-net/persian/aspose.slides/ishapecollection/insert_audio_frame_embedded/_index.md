---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
یک قاب صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده درج می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios افزوده می‌شود.

### بازگشت
[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) جدید ایجاد شده.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص صفر مبنایی که در آن قاب صوتی درج می‌شود. |
| x | **float** | مختصات x قاب صوتی جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب صوتی جدید، به واحد نقطه. |
| width | **float** | عرض قاب صوتی جدید، به واحد نقطه. |
| height | **float** | ارتفاع قاب صوتی جدید، به واحد نقطه. |
| audio_stream | **io.RawIOBase** | یک جریان ورودی که شامل داده‌های صوتی WAV برای جاسازی است. |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
یک قاب صوتی جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده با استفاده از یک شی صوتی موجود از فهرست Presentation.Audios درج می‌نماید.

### بازگشت
[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) جدید ایجاد شده.

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص صفر مبنایی که در آن قاب صوتی درج می‌شود. |
| x | **float** | مختصات x قاب صوتی جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب صوتی جدید، به واحد نقطه. |
| width | **float** | عرض قاب صوتی جدید، به واحد نقطه. |
| height | **float** | ارتفاع قاب صوتی جدید، به واحد نقطه. |
| audio | [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) | یک نمونه [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) از مجموعهٔ Presentation.Audios برای جاسازی. |

### موارد مرتبط
* کلاس [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio)
* کلاس [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)