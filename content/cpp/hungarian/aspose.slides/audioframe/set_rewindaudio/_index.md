---
title: set_RewindAudio()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a hang automatikusan visszatekerődik-e a lejátszás után a kezdetre. Írja bool.
type: docs
weight: 248
url: /hu/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) metódus


Meghatározza, hogy a hang automatikusan visszatekerődik-e a lejátszás után a kezdetre. Írja **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Megjegyzések



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

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)