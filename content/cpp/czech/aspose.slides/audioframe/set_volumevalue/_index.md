---
title: set_VolumeValue()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Nastavuje hlasitost zvuku v procentech. Zapište float.
type: docs
weight: 391
url: /cs/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) metoda


Nastavuje hlasitost zvuku v procentech. Zapište **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat zvukový rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavte dobu trvání úvodního přechodu na 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)