---
title: get_Audios()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu IAudioCollection.
type: docs
weight: 222
url: /pl/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metoda


Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Uwagi


Poniższe przykłady pokazują, jak dodać hiperłącze do pliku audio. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioCollection](../../iaudiocollection/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)