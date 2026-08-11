---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ إطار صوتي جديد بملف WAV مضمّن ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios.
type: docs
weight: 261
url: /ar/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) طريقة

ينشئ إطار صوتي جديد بملف WAV مضمّن ويُدخله في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس القائم على الصفر الذي سيتم إدراج إطار الصوت عنده. |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق إدخال يحتوي على بيانات صوتية بصيغة WAV لتضمينها. |

### قيمة الإرجاع

الـ[IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) طريقة

ينشئ إطار صوتي جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس القائم على الصفر الذي سيتم إدراج إطار الصوت عنده. |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | مثيل [IAudio](../../iaudio/) من مجموعة Presentation.Audios لتضمينه. |

### قيمة الإرجاع

الـ[IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudioFrame](../../iaudioframe/)
* فئة [Stream](../../../system.io/stream/)
* فئة [IShapeCollection](../)
* فئة [IAudio](../../iaudio/)
* نطاق الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)