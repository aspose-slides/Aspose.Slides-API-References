---
title: set_TrimFromEnd()
second_title: Aspose.Slides C++ API Referenciája
description: Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Írja float.
type: docs
weight: 443
url: /hu/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) method


Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Írja **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
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