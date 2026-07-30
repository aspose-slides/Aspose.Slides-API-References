---
title: get_VolumeValue()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací hlasitost zvuku v procentech. Čte float.
type: docs
weight: 378
url: /cs/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() metoda


Vrací hlasitost zvuku v procentech. Čte **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat zvukový rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit dobu trvání úvodního zeslabení na 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)