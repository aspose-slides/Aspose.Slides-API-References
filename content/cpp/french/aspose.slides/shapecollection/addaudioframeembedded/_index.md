---
title: AddAudioFrameEmbedded()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection Presentation::get_Audios."
type: docs
weight: 287
url: /fr/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) méthode

Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la collection de formes. L'audio intégré est ajouté à la collection [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux d'entrée contenant des données audio WAV à intégrer. |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Remarques

L'exemple suivant montre comment créer le cadre [Audio](../../audio/).
```cpp
// Instancie une classe de présentation qui représente un fichier de présentation
auto pres = System::MakeObject<Presentation>();

// Récupère la première diapositive
auto slide = pres->get_Slides()->idx_get(0);
// Charge le fichier son wav dans le flux
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Ajoute le cadre audio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Définit le mode de lecture et le volume de l'audio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Écrit le fichier PowerPoint sur le disque
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) méthode

Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un objet audio existant provenant de la liste [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre audio, en points. |
| y | **float** | La coordonnée y du nouveau cadre audio, en points. |
| width | **float** | La largeur du nouveau cadre audio, en points. |
| height | **float** | La hauteur du nouveau cadre audio, en points. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Une instance [IAudio](../../iaudio/) provenant de la collection [Presentation::get_Audios](../../presentation/get_audios/). |

### Valeur de retour

Le [IAudioFrame](../../iaudioframe/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [ShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)