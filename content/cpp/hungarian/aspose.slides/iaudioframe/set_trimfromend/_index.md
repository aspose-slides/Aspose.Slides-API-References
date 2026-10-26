---
title: set_TrimFromEnd()
second_title: Aspose.Slides C++ API referencia
description: Megadja a lejátszás során a médiából a végén eltávolítandó időtartamot ezredmásodpercben. Írja float.
type: docs
weight: 443
url: /hu/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) metódus


Megadja a lejátszás során a médiából a végén eltávolítandó időtartamot ezredmásodpercben. Írja **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
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

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)