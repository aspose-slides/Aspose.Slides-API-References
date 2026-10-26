---
title: get_FadeInDuration()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje časovou délku počátečního fade-in média v milisekundách. Čte float.
type: docs
weight: 326
url: /cs/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() metoda


Určuje časovou délku počátečního fade-in média v milisekundách. Čte **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat zvukový rámec
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)