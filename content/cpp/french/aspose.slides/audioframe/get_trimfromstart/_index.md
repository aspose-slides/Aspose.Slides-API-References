---
title: get_TrimFromStart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. Lecture float.
type: docs
weight: 404
url: /fr/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() méthode


Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. Lecture **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir le temps de coupe initial à 1,5 seconde
audioFrame->set_TrimFromStart(1500.0f);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)