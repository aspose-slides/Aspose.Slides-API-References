---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.
type: docs
weight: 248
url: /fa/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) متد

یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌سازد. صوت جاسازی‌شده به مجموعهٔ Presentation.Audios اضافه می‌شود.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم صوتی جدید، به نقاط. |
| y | **float** | مختصات y فریم صوتی جدید، به نقاط. |
| width | **float** | عرض فریم صوتی جدید، به نقاط. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقاط. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان ورودی حاوی داده‌های صوتی WAV برای جاسازی. |

### مقدار بازگشت

‏[IAudioFrame](../../iaudioframe/) جدید ایجاد شده.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) متد

یک فریم صوتی جدید ایجاد می‌کند و آن را با استفاده از شی صوتی موجود در فهرست Presentation.Audios به انتهای مجموعهٔ اشکال اضافه می‌سازد.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم صوتی جدید، به نقاط. |
| y | **float** | مختصات y فریم صوتی جدید، به نقاط. |
| width | **float** | عرض فریم صوتی جدید، به نقاط. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقاط. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | یک نمونهٔ [IAudio](../../iaudio/) از مجموعهٔ Presentation.Audios. |

### مقدار بازگشت

‏[IAudioFrame](../../iaudioframe/) جدید ایجاد شده.

## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudioFrame](../../iaudioframe/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [IShapeCollection](../)
* کلاس [IAudio](../../iaudio/)
* فضا نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)