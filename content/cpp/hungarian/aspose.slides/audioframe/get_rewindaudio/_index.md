---
title: get_RewindAudio()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a hang automatikusan visszatekerődik-e a lejátszás után a kezdőpontra. Olvasás bool.
type: docs
weight: 235
url: /hu/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() metódus


Megállapítja, hogy a hang automatikusan visszatekerődik-e a lejátszás után a kezdőpontra. Olvasás **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Hangkeret hozzáadása
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)