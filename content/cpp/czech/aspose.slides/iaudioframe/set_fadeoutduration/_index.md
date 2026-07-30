---
title: set_FadeOutDuration()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje časové trvání koncového zeslabení média v milisekundách. Zapište float.
type: docs
weight: 365
url: /cs/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) metoda


Určuje časové trvání koncového zeslabení médií v milisekundách. Zapište **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Přidat Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Nastavit dobu trvání koncového zeslabení na 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IAudioFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)