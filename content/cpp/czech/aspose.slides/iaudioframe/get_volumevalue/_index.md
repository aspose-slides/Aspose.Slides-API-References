---
title: get_VolumeValue()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hlasitost zvuku v procentech. Čte float.
type: docs
weight: 378
url: /cs/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() metoda


Vrací hlasitost zvuku v procentech. Čte **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavte dobu trvání úvodního prolínání na 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)