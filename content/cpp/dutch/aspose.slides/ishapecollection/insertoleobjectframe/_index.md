---
title: InsertOleObjectFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw OLE-objectframe en voegt het toe aan de vormverzameling op de opgegeven index.
type: docs
weight: 79
url: /nl/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Maakt een nieuw OLE-objectframe en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | De ingebedde OLE-gegevensinformatie ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Retourwaarde

Het nieuw gemaakte [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method

Maakt een nieuw OLE-objectframe en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| className | [System::String](../../../system/string/) | De klassenaam van het OLE-object. |
| path | [System::String](../../../system/string/) | Het pad naar het gekoppelde bestand. |

### Retourwaarde

Het nieuw gemaakte [IOleObjectFrame](../../ioleobjectframe/).

## Opmerkingen

Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad is opgegeven, zal het bestand ontoegankelijk zijn bij het openen van de presentatie vanuit een andere map.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)