---
title: get_FadeOutDuration()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la durée temporelle du fondu de sortie final du média en millisecondes. Lecture float.
type: docs
weight: 352
url: /fr/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() méthode

Spécifie la durée temporelle du fondu de sortie final du média en millisecondes. Lecture **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir la durée du fondu de fin à 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)