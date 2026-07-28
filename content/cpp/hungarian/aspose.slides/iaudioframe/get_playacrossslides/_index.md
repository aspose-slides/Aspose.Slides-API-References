---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a hang a diákokon keresztül lejátszásra kerül-e. Olvasás bool.
type: docs
weight: 209
url: /hu/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() metódus


Megállapítja, hogy a hang a diákokon keresztül lejátszásra kerül-e. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Hangkeret hozzáadása
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Hang beállítása a diákokon át történő lejátszáshoz
audioFrame->set_PlayAcrossSlides(true);

// Hang automatikus visszatekerése a lejátszás után
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lásd még

* Osztály [IAudioFrame](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)