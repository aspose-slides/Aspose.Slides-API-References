---
title: get_TrimFromEnd()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasandó float.
type: docs
weight: 430
url: /hu/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() metódus


Meghatározza a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasandó **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Megjegyzések


Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a végvágási időt 2 másodpercre
audioFrame->set_TrimFromEnd(2000.0f);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)