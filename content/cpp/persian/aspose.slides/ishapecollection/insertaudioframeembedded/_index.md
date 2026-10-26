---
title: InsertAudioFrameEmbedded()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص‌شده درج می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.
type: docs
weight: 261
url: /fa/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) متد

یک فریم صوتی جدید با یک فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص‌شده درج می‌نماید. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-پایه‌ای که فریم صوتی در آن درج می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینت. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

### مقدار بازگشت

[IAudioFrame](../../iaudioframe/) جدید ایجاد شده.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) متد

یک فریم صوتی جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص‌شده با استفاده از یک شیء صوتی موجود از فهرست Presentation.Audios درج می‌نماید.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-پایه‌ای که فریم صوتی در آن درج می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینت. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | یک نمونهٔ [IAudio](../../iaudio/) از مجموعهٔ Presentation.Audios برای جاسازی. |

### مقدار بازگشت

[IAudioFrame](../../iaudioframe/) جدید ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudioFrame](../../iaudioframe/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [IShapeCollection](../)
* کلاس [IAudio](../../iaudio/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)