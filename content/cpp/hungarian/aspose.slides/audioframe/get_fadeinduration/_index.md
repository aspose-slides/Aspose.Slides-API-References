---
title: get_FadeInDuration()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Olvasható float.
type: docs
weight: 326
url: /hu/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metódus


Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Olvasható **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio Frame hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdeti fade időtartamát 200 ms-re
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)