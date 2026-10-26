---
title: AddVideoFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw video-frame en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 170
url: /nl/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) methode


Maakt een nieuw video-frame en voegt het toe aan het einde van de shape-collectie.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | **float** | De breedte van het nieuwe video-frame, in punten. |
| height | **float** | De hoogte van het nieuwe video-frame, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het videobestand om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) methode


Maakt een nieuw video-frame en voegt het toe aan het einde van de shape-collectie.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe video-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe video-frame, in punten. |
| width | **float** | De breedte van het nieuwe video-frame, in punten. |
| height | **float** | De hoogte van het nieuwe video-frame, in punten. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | De [IVideo](../../ivideo/) om in het video-frame in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Klasse [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)