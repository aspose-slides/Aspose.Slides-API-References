---
title: get_FadeOutDuration()
second_title: Aspose.Slides C++ API referencia
description: Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasható float.
type: docs
weight: 352
url: /hu/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() metódus


Megadja a média befejező elhalványulásának időtartamát ezredmásodpercben. Olvasható **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio keret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a befejező elhalványulás időtartamát 500 ms-re
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)