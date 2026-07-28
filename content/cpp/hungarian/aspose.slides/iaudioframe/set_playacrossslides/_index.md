---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides C++ API Referencia
description: Megállapítja, hogy az audio a diákok között játszódik-e. Írja bool.
type: docs
weight: 222
url: /hu/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) metódus


Megállapítja, hogy az audio a diákok között játszódik-e. Írja **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Hangkeret hozzáadása
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Beállítja, hogy a hang a diákok között játsszon
audioFrame->set_PlayAcrossSlides(true);

// Beállítja, hogy a hang automatikusan visszatekerjen a kezdőpontra a lejátszás után
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Lásd még

* Osztály [IAudioFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)