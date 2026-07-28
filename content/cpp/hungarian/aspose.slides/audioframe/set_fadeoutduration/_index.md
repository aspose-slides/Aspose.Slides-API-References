---
title: set_FadeOutDuration()
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza a média befejező elhalkulásának időtartamát ezredmásodpercben. Írja float.
type: docs
weight: 365
url: /hu/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) metódus

Meghatározza az időtartamot a média befejező elhalkulásához ezredmásodpercben. Írja **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a befejező elhalkulás időtartamát 500 ms-re
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)