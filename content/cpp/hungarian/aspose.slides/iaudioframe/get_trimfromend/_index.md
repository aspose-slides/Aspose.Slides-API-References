---
title: get_TrimFromEnd()
second_title: Aspose.Slides C++ API Referencia
description: Megadja a lejátszás során a média végéről eltávolítandó időtartamot, ezredmásodpercben. Olvasás float.
type: docs
weight: 430
url: /hu/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() metódus


Megadja az időtartamot, amelyet a lejátszás során a média végéről kell eltávolítani, ezredmásodpercben. Olvasás **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a végvágás idejét 2 másodpercre
audioFrame->set_TrimFromEnd(2000.0f);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)