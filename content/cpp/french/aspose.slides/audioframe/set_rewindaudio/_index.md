---
title: set_RewindAudio()
second_title: Aspose.Slides pour la référence API C++
description: Détermine si l'audio est automatiquement rembobiné au début après la lecture. Écrire bool.
type: docs
weight: 248
url: /fr/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) méthode


Détermine si l'audio est automatiquement rembobiné au début après la lecture. Écrire **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ajouter un cadre audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Définir l'audio pour qu'il se joue sur toutes les diapositives
audioFrame->set_PlayAcrossSlides(true);

// Définir l'audio pour qu'il rembobine automatiquement au début après la lecture
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)