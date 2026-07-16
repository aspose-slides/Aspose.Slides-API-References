---
title: get_Audios()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule IAudioCollection.
type: docs
weight: 222
url: /fr/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() méthode

Renvoie la collection de tous les fichiers audio intégrés dans la présentation. En lecture seule [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Remarques

L'exemple suivant montre comment ajouter un hyperlien vers un fichier audio. ```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioCollection](../../iaudiocollection/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)