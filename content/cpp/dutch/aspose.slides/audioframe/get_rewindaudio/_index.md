---
title: get_RewindAudio()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of audio automatisch wordt teruggespoeld naar het begin na het afspelen. Lezen bool.
type: docs
weight: 235
url: /nl/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() methode


Bepaalt of audio automatisch wordt teruggespoeld naar het begin na het afspelen. Lezen **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Opmerkingen



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Zie ook

* Klasse [AudioFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)