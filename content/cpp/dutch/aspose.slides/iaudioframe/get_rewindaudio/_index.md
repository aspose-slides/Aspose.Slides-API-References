---
title: get_RewindAudio()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of een audio automatisch wordt teruggedraaid naar het begin na het afspelen. Lees bool.
type: docs
weight: 235
url: /nl/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() methode


Bepaalt of een audio automatisch wordt teruggedraaid naar het begin na het afspelen. Lees **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audioframe toevoegen
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Audio instellen om door de dia's af te spelen
audioFrame->set_PlayAcrossSlides(true);

// Audio instellen om automatisch terug te spoelen naar het begin na afspelen
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Zie ook

* Klasse [IAudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)