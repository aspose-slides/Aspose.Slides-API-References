---
title: set_FadeOutDuration()
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza a média befejező fade-out időtartamát ezredmásodpercben. Írja float.
type: docs
weight: 365
url: /hu/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) metódus


Meghatározza a média befejező fade-out időtartamát ezredmásodpercben. Írja **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a befejező fade időtartamát 500 ms-re
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)