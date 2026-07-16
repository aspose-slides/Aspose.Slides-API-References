---
title: get_FadeInDuration()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la durée du fondu d’entrée initial du média en millisecondes. Lecture float.
type: docs
weight: 326
url: /fr/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() méthode


Spécifie la durée du fondu d'entrée initial du média en millisecondes. Lecture **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Remarques


Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir la durée du fondu d'entrée à 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)