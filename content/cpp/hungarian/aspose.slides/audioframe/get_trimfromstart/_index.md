---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API hivatkozás
description: Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasható float.
type: docs
weight: 404
url: /hu/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() metódus


Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasható **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audiókeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdő vágási időt 1.5 másodperc
audioFrame->set_TrimFromStart(1500.0f);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)