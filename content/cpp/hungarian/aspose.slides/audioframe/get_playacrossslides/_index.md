---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy a hang a diákokon keresztül játszódik-e. Olvas bool.
type: docs
weight: 209
url: /hu/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() metódus

Megállapítja, hogy a hang a diákokon keresztül játszódik-e. Olvas **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Megjegyzések


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Hangkeret hozzáadása
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Beállítja, hogy a hang a diákokon keresztül játsszon
audioFrame->set_PlayAcrossSlides(true);

// Beállítja, hogy a hang automatikusan visszatekerődjön a kezdetre lejátszás után
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Lásd még

* Osztály [AudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)