---
title: set_PlayAcrossSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si le son est lu à travers les diapositives. Écrire bool.
type: docs
weight: 222
url: /fr/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) méthode


Détermine si le son est lu à travers les diapositives. Écrire **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ajouter une trame audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Configurer le son pour qu'il se joue sur toutes les diapositives
audioFrame->set_PlayAcrossSlides(true);

// Configurer le son pour qu'il revienne automatiquement au début après la lecture
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)