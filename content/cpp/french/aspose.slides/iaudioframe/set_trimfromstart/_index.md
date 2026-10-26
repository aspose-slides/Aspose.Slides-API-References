---
title: set_TrimFromStart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la durée à supprimer du début du média lors de la lecture, en millisecondes. Écrire float.
type: docs
weight: 417
url: /fr/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) méthode


Spécifie la durée à supprimer du début du média lors de la lecture, en millisecondes. Écrire **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir le temps de découpage du début à 1,5 secondes
audioFrame->set_TrimFromStart(1500.0f);
```

## Voir aussi

* Classe [IAudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)