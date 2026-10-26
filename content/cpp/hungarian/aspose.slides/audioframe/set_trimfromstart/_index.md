---
title: set_TrimFromStart()
second_title: Aspose.Slides a C++ API referencia
description: Meghatározza a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Írja float.
type: docs
weight: 417
url: /hu/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) metódus

Megadja az eltávolítandó időtartamot a média elejéről lejátszás közben, ezredmásodpercben. Írja **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Megjegyzések

Példa:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdő vágási időt 1.5 másodpercre
audioFrame->set_TrimFromStart(1500.0f);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)