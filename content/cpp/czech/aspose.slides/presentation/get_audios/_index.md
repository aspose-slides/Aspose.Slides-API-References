---
title: get_Audios()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací kolekci všech vložených audio souborů v prezentaci. Pouze pro čtení IAudioCollection.
type: docs
weight: 222
url: /cs/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metoda

Vrací kolekci všech vložených audio souborů v prezentaci. Pouze pro čtení [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Poznámky

Následující příklady ukazují, jak přidat hypertextový odkaz na audio soubor. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudioCollection](../../iaudiocollection/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)