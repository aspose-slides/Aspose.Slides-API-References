---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides برای C++ مرجع API
description: "یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعه اشکال در اندیس مشخص شده وارد می‌گیرد. صوت جاسازی‌شده به مجموعه Presentation::get_Audios اضافه می‌شود."
type: docs
weight: 300
url: /fa/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) متد

یک فریم صوتی جدید با فایل WAV جاسازی‌شده ایجاد می‌کند و آن را در مجموعه اشکال در اندیس مشخص شده وارد می‌گیرد. صوت جاسازی‌شده به مجموعه [Presentation::get_Audios](../../presentation/get_audios/) اضافه می‌شود.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا که فریم صوتی در آن وارد می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینت. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

### مقدار بازگشت

[IAudioFrame](../../iaudioframe/) تازه ایجاد شده.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) متد

یک فریم صوتی جدید ایجاد می‌کند و آن را در مجموعه اشکال در اندیس مشخص شده با استفاده از شی صوتی موجود از فهرست [Presentation::get_Audios](../../presentation/get_audios/) وارد می‌گیرد.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنا که فریم صوتی در آن وارد می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب پوینت. |
| width | **float** | عرض فریم صوتی جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب پوینت. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | یک نمونه [IAudio](../../iaudio/) از مجموعه [Presentation::get_Audios](../../presentation/get_audios/) برای جاسازی. |

### مقدار بازگشت

[IAudioFrame](../../iaudioframe/) تازه ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudioFrame](../../iaudioframe/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [ShapeCollection](../)
* کلاس [IAudio](../../iaudio/)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)