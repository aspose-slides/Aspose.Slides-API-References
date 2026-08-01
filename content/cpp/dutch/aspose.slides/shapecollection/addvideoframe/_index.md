---
title: AddVideoFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw videokader aan en voegt het toe aan het einde van de shapecollectie.
type: docs
weight: 209
url: /nl/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) methode

Maakt een nieuw videokader aan en voegt het toe aan het einde van de shapecollectie.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe videokader, in punten. |
| y | **float** | De y-coördinaat van het nieuwe videokader, in punten. |
| width | **float** | De breedte van het nieuwe videokader, in punten. |
| height | **float** | De hoogte van het nieuwe videokader, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het videobestand om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) methode

Maakt een nieuw videokader aan en voegt het toe aan het einde van de shapecollectie.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe videokader, in punten. |
| y | **float** | De y-coördinaat van het nieuwe videokader, in punten. |
| width | **float** | De breedte van het nieuwe videokader, in punten. |
| height | **float** | De hoogte van het nieuwe videokader, in punten. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | De [IVideo](../../ivideo/) om in te sluiten in het videokader. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IVideoFrame](../../ivideoframe/)
* Klasse [String](../../../system/string/)
* Klasse [ShapeCollection](../)
* Klasse [IVideo](../../ivideo/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)