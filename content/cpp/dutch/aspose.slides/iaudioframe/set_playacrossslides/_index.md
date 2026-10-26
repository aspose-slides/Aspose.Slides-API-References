---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt of een audio wordt afgespeeld over de dia's. Schrijf bool.
type: docs
weight: 222
url: /nl/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) methode


Bepaalt of een audio wordt afgespeeld over de dia's. Schrijf **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Voeg audioframe toe
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Stel Audio in om over de dia's af te spelen
audioFrame->set_PlayAcrossSlides(true);

// Stel Audio in om automatisch naar het begin terug te spoelen na afspelen
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)