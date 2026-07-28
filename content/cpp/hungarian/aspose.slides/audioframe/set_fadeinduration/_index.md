---
title: set_FadeInDuration()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Írja float.
type: docs
weight: 339
url: /hu/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) metódus


Meghatározza a média kezdeti fade-in időtartamát ezredmásodpercben. Írja **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdő fade időtartamát 200 ms-re
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)