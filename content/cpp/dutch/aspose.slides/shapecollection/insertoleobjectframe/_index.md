---
title: InsertOleObjectFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw OLE objectframe en voegt het in de shape collection in op de opgegeven index.
type: docs
weight: 196
url: /nl/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) methode

Maakt een nieuw OLE-objectframe en voegt het in de shape collection in op de opgegeven index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | De ingebedde OLE-data-informatie ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Retourwaarde

Het nieuw aangemaakte [IOleObjectFrame](../../ioleobjectframe/).

## Opmerkingen



Dit voorbeeld laat zien hoe een OLE-object op de tweede index wordt ingevoegd:
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) methode

Maakt een nieuw OLE-objectframe en voegt het in de shape collection in op de opgegeven index.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| className | [System::String](../../../system/string/) | De klassenaam van het OLE-object. |
| path | [System::String](../../../system/string/) | Het pad naar het gekoppelde bestand. |

### Retourwaarde

Het nieuw aangemaakte OLE-objectframe.

## Opmerkingen



Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, is het bestand niet toegankelijk bij het openen van de presentatie vanuit een andere map.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOleObjectFrame](../../ioleobjectframe/)
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [ShapeCollection](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)