---
title: AddAudioFrameEmbedded()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يقوم بإنشاء إطار صوت جديد مع ملف WAV مضمن ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المضمن إلى مجموعة Presentation.Audios.
type: docs
weight: 248
url: /ar/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) طريقة

يقوم بإنشاء إطار صوت جديد مع ملف WAV مضمن ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المضمن إلى مجموعة Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق إدخال يحتوي على بيانات صوتية بصيغة WAV لتضمينه. |

### قيمة الإرجاع

الـ [IAudioFrame](../../iaudioframe/) تم إنشاؤه حديثًا.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) طريقة

يقوم بإنشاء إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | مثيل [IAudio](../../iaudio/) من مجموعة Presentation.Audios. |

### قيمة الإرجاع

الـ [IAudioFrame](../../iaudioframe/) تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAudioFrame](../../iaudioframe/)
* فئة [Stream](../../../system.io/stream/)
* فئة [IShapeCollection](../)
* فئة [IAudio](../../iaudio/)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)