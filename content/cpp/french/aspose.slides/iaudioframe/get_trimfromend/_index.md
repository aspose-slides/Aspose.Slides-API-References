---
title: get_TrimFromEnd()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. Lecture float.
type: docs
weight: 430
url: /fr/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() méthode

Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. Lecture **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## Remarques

Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir le temps de rognage à la fin à 2 secondes
audioFrame->set_TrimFromEnd(2000.0f);
```

## Voir aussi

* Classe [IAudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)