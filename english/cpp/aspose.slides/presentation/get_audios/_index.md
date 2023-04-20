---
title: get_Audios()
second_title: Aspose.Slides for C++ API Reference
description: Returns the collection of all embedded audio files in the presentation. Read-only IAudioCollection.
type: docs
weight: 222
url: /cpp/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() method


Returns the collection of all embedded audio files in the presentation. Read-only [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Remarks


The following examples shows how to add a hyperlink to an audio file. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioCollection](../../iaudiocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)