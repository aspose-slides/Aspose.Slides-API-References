---
title: set_VolumeValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le volume audio en pourcentage. Écrivez float.
type: docs
weight: 391
url: /fr/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) méthode


Définit le volume audio en pourcentage. Écrivez **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## Remarques


Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir la durée du fondu d'ouverture à 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IAudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)