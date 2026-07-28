---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API referencia
description: Megadja a lejátszás során a médiától az elejéről eltávolítandó időtartamot, ezredmásodpercben. Olvasható float.
type: docs
weight: 404
url: /hu/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() metódus


Meghatározza az eltávolítandó időtartamot a média elejéről lejátszás közben, ezredmásodpercben. Olvasható **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio keret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsd be a kezdő vágási időt 1,5 másodpercre
audioFrame->set_TrimFromStart(1500.0f);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)