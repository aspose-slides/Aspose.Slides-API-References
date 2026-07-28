---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API-referencia
description: Meghatározza, hogy egy hang automatikusan visszatekerődik-e a lejátszás után az elejére. Írjon bool.
type: docs
weight: 248
url: /hu/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) metódus

Meghatározza, hogy egy hang automatikusan visszatekerődik-e az elejére a lejátszás után. Írja **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
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

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)