---
title: add_audio_frame_embedded method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
یک فریم صوتی جدید با فایل WAV تعبیه‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. صدای تعبیه‌شده به مجموعه Presentation.Audios اضافه می‌شود.

### Returns

[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) تازه ایجاد شده.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | **float** | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio_stream | **io.RawIOBase** | یک جریان ورودی حاوی داده‌های صوتی WAV برای تعبیه. |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
یک فریم صوتی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید با استفاده از یک شی صوتی موجود از فهرست Presentation.Audios.

### Returns

[`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe) تازه ایجاد شده.

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | **float** | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio | [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) | یک نمونهٔ [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio) از مجموعه Presentation.Audios. |

### See Also
* class [`IAudio`](/slides/python-net/fa/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/fa/aspose.slides/iaudioframe)
* class [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)