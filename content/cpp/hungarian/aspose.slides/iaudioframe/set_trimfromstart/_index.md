---
title: set_TrimFromStart()
second_title: Aspose.Slides C++ API referenciája
description: Megadja a lejátszás során a médiától az elejéről eltávolítandó időtartamot ezredmásodpercben. Írja float.
type: docs
weight: 417
url: /hu/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) metódus


Megadja a lejátszás során a médiától az elejéről eltávolítandó időtartamot ezredmásodpercben. Írja **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdeti vágási időt 1,5 másodperc
audioFrame->set_TrimFromStart(1500.0f);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)