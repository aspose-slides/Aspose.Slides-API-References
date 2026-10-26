---
title: AddAudioFrameEmbedded()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "ينشئ إطار صوت جديد مع ملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation::get_Audios."
type: docs
weight: 287
url: /ar/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) طريقة


يُنشئ إطار صوت جديد مع ملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

### قيمة الإرجاع

[IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## ملاحظات



الأمثلة التالية توضح كيفية إنشاء إطار [Audio](../../audio/). 
```cpp
// ينشئ كائنًا من فئة العرض التي تمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>();

// يحصل على الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);
// يحمل ملف الصوت wav إلى تدفق
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// يضيف إطار الصوت
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// يحدد وضع التشغيل وحجم الصوت
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// يكتب ملف PowerPoint إلى القرص
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) طريقة


يُنشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي x لإطار الصوت الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | نسخة [IAudio](../../iaudio/) من مجموعة [Presentation::get_Audios](../../presentation/get_audios/). |

### قيمة الإرجاع

[IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IAudioFrame](../../iaudioframe/)
* الفئة [Stream](../../../system.io/stream/)
* الفئة [ShapeCollection](../)
* الفئة [IAudio](../../iaudio/)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)