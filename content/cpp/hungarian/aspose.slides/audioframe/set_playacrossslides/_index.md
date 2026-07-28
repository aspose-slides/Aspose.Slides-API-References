---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides C++ API Referencia
description: Meghatározza, hogy a hang a diákon keresztül játszódik-e. Írja bool.
type: docs
weight: 222
url: /hu/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) metódus


Meghatározza, hogy a hang a diákon keresztül játszódik-e. Írja **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio Frame hozzáadása
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Állítsa be, hogy az audio a diákon keresztül játsszon
audioFrame->set_PlayAcrossSlides(true);

// Állítsa be, hogy az audio automatikusan visszaálljon az elejére a lejátszás után
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)