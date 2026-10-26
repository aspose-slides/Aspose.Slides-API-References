---
title: get_RewindAudio()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si l'audio est automatiquement rembobiné au début après la lecture. Lire bool.
type: docs
weight: 235
url: /fr/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() méthode


Détermine si l'audio est automatiquement rembobiné au début après la lecture. Lire **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ajouter une trame audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Définir l'audio pour qu'il rembobine automatiquement au début après la lecture
audioFrame->set_PlayAcrossSlides(true);

// Définir l'audio pour qu'il rembobine automatiquement au début après la lecture
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)