---
title: get_PlayAcrossSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le son est lu sur toutes les diapositives. Lecture bool.
type: docs
weight: 209
url: /fr/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() méthode

Détermine si le son est lu sur toutes les diapositives. Lecture **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ajouter un cadre audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Configurer l'audio pour qu'il soit lu sur toutes les diapositives
audioFrame->set_PlayAcrossSlides(true);

// Configurer l'audio pour qu'il rembobine automatiquement au début après la lecture
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)