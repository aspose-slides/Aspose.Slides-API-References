---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides برای C++ مرجع API
description: "یک فریم صوتی جدید با یک فایل WAV تعبیه‌شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌گردد. صوت تعبیه‌شده به مجموعه Presentation::get_Audios افزوده می‌شود."
type: docs
weight: 287
url: /fa/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) متد


یک فریم صوتی جدید با یک فایل WAV تعبیه‌شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند. صوت تعبیه‌شده به مجموعه [Presentation::get_Audios](../../presentation/get_audios/) اضافه می‌شود.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم صوتی جدید، به نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، به نقطه. |
| width | **float** | عرض فریم صوتی جدید، به نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقطه. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان ورودی حاوی داده‌های صوتی WAV برای تعبیه. |

### مقدار بازگردانده

[IAudioFrame](../../iaudioframe/) تازه ایجاد شده.

## توضیحات



مثال‌های زیر نشان می‌دهند چگونه [Audio](../../audio/) قاب را ایجاد کنید. 
```cpp
// یک شی ارائه می‌سازد که نمایانگر یک فایل ارائه است
auto pres = System::MakeObject<Presentation>();

// اولین اسلاید را دریافت می‌کند
auto slide = pres->get_Slides()->idx_get(0);
// فایل صوتی wav را به جریان بارگذاری می‌کند
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// فریم صوتی را اضافه می‌کند
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// حالت پخش و حجم صدا را تنظیم می‌کند
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// فایل PowerPoint را بر روی دیسک می‌نویسد
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) متد


یک فریم صوتی جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند با استفاده از یک شی صوتی موجود از لیست [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم صوتی جدید، به نقطه. |
| y | **float** | مختصات y فریم صوتی جدید، به نقطه. |
| width | **float** | عرض فریم صوتی جدید، به نقطه. |
| height | **float** | ارتفاع فریم صوتی جدید، به نقطه. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | یک نمونه [IAudio](../../iaudio/) از مجموعه [Presentation::get_Audios](../../presentation/get_audios/). |

### مقدار بازگردانده

[IAudioFrame](../../iaudioframe/) تازه ایجاد شده.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)