---
title: set_PlayAcrossSlides()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si un audio est lu sur toutes les diapositives. Écrit bool.
type: docs
weight: 222
url: /fr/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) méthode


Détermine si un audio est lu sur toutes les diapositives. Écrit **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## Remarques



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Ajouter une trame audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Définir l'audio pour être lu sur toutes les diapositives
audioFrame->set_PlayAcrossSlides(true);

// Définir l'audio pour rembobiner automatiquement au début après la lecture
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## Voir aussi

* Classe [IAudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)