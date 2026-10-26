---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API hivatkozás
description: Visszaadja a hangerőt százalékban. Olvasás float.
type: docs
weight: 378
url: /hu/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metódus

Visszaadja a hanghangerőt százalékban. Olvasás **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Megjegyzés

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Audio Frame hozzáadása
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Állítsa be a kezdő elhalványulás időtartamát 200 ms-re
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)