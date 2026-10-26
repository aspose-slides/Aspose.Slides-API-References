---
title: AddOleObjectFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 66
url: /nl/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) methode

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | De ingesloten OLE-gegevensinformatie ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Returnwaarde

De nieuw aangemaakte [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) methode

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| className | [System::String](../../../system/string/) | De klassenaam van het OLE-object. |
| path | [System::String](../../../system/string/) | Het pad naar het gekoppelde bestand. |

### Returnwaarde

De nieuw aangemaakte [IOleObjectFrame](../../ioleobjectframe/).

## Opmerkingen

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, zal het bestand ontoegankelijk zijn bij het openen van de presentatie vanuit een andere map.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOleObjectFrame](../../ioleobjectframe/)
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [IShapeCollection](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)