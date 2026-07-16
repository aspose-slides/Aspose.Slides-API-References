---
title: set_VolumeValue()
second_title: Référence API Aspose.Slides pour C++
description: Définit le volume audio en pourcentage. Écrire float.
type: docs
weight: 391
url: /fr/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) méthode


Définit le volume audio en pourcentage. Écrire **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Ajouter une trame audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Définir la durée du fondu de démarrage à 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)