---
title: get_FadeOutDuration()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje časovou délku koncového zeslabení média v milisekundách. Čte float.
type: docs
weight: 352
url: /cs/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() metoda

Určuje časovou délku koncového zeslabení média v milisekundách. Čte **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat audio rámeček
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [AudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)