---
title: get_FadeOutDuration()
second_title: Aspose.Slides C++ API hivatkozás
description: Megadja a média végső elhalkulásának időtartamát ezredmásodpercben. Olvasás float.
type: docs
weight: 352
url: /hu/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metódus

Megadja a média végső elhalkulásának időtartamát ezredmásodpercben. Olvasás **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a végső elhalkulás időtartamát 500 ms-re
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)