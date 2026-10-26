---
title: InsertAudioFrameEmbedded()
second_title: مرجع API Aspose.Slides للغة C++
description: "إنشاء إطار صوتي جديد يحتوي على ملف WAV مضمّن وإدراجه في مجموعة الأشكال عند الفهرس المحدد. يُضاف الصوت المضمّن إلى مجموعة Presentation::get_Audios."
type: docs
weight: 300
url: /ar/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ إطار صوتي جديد يحتوي على ملف WAV مضمّن ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يُضاف الصوت المضمّن إلى مجموعة [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس القائم على الصفر الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق إدخال يحتوي على بيانات صوتية WAV لتضمينها. |

### قيمة الإرجاع

الكائن [IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) طريقة

ينشئ إطار صوتي جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس القائم على الصفر الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | نسخة [IAudio](../../iaudio/) من مجموعة [Presentation::get_Audios](../../presentation/get_audios/) لتضمينها. |

### قيمة الإرجاع

الكائن [IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)