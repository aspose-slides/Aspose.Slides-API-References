---
title: set_TrimFromEnd()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Écrire float.
type: docs
weight: 443
url: /fr/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) méthode


Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Écrire **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## Remarques


Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir le temps de rognage à la fin à 2 secondes
audioFrame->set_TrimFromEnd(2000.0f);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)