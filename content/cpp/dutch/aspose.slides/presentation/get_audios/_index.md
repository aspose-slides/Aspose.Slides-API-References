---
title: get_Audios()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de collectie van alle ingesloten audiobestanden in de presentatie. Alleen-lezen IAudioCollection.
type: docs
weight: 222
url: /nl/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() methode

Retourneert de verzameling van alle ingebedde audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Opmerkingen

De volgende voorbeelden laten zien hoe je een hyperlink aan een audiobestand kunt toevoegen. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioCollection](../../iaudiocollection/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)