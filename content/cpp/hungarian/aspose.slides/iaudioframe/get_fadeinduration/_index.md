---
title: get_FadeInDuration()
second_title: Aspose.Slides C++ API Referencia
description: Megadja a média kezdeti beolvadásának időtartamát ezredmásodpercben. Olvasás float.
type: docs
weight: 326
url: /hu/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() metódus


Meghatározza a média kezdeti beolvadásának időtartamát ezredmásodpercben. Olvasás **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio keret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdő elhalványulás időtartamát 200 ms-re
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)