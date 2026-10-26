---
title: get_VolumeValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le volume audio en pourcentage. Lecture float.
type: docs
weight: 378
url: /fr/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() méthode


Renvoie le volume audio en pourcentage. Lecture **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Remarques


Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter un cadre audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir la durée du fondu d'entrée à 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)