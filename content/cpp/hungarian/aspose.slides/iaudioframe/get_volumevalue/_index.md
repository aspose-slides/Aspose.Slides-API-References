---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a hang hangerő értékét százalékban. Olvasás float.
type: docs
weight: 378
url: /hu/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() metódus


Visszaadja a hang hangerő értékét százalékban. Olvasás **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Hangkeret hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)