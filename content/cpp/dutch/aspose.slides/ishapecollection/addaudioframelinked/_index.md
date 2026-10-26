---
title: AddAudioFrameLinked()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw audioframe gekoppeld aan een extern audio-bestand en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 222
url: /nl/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) method


Maakt een nieuw audio-frame dat is gekoppeld aan een extern audio-bestand en voegt het toe aan het einde van de shape-collectie.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe audio-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audio-frame, in punten. |
| width | **float** | De breedte van het nieuwe audio-frame, in punten. |
| height | **float** | De hoogte van het nieuwe audio-frame, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het externe audio-bestand om te koppelen. |

### Retourwaarde

De nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)