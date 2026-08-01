---
title: AddOleObjectFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 183
url: /nl/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | De informatie over de ingebedde OLE-gegevens ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Retourwaarde

Het nieuw aangemaakte [IOleObjectFrame](../../ioleobjectframe/).

## Opmerkingen



De volgende voorbeelden laten zien hoe OLE-objectframes toe te voegen aan [Slides](../../) van PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Toegang tot de eerste dia
auto slide = pres->get_Slides()->idx_get(0);
// Laadt een Excel-bestand naar een stream
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Maakt een data-object voor insluiten
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Voegt een OLE-objectframe toe
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Schrijft het PPTX-bestand naar schijf
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| className | [System::String](../../../system/string/) | De klassenaam van het OLE-object. |
| path | [System::String](../../../system/string/) | Het pad naar het gekoppelde bestand. |

### Retourwaarde

Het nieuw aangemaakte [IOleObjectFrame](../../ioleobjectframe/).

## Opmerkingen



Dit pad wordt letterlijk opgeslagen in de presentatie. Als een relatief pad wordt opgegeven, is het bestand niet toegankelijk bij het openen van de presentatie vanuit een andere map.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IOleObjectFrame](../../ioleobjectframe/)
* Klasse [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasse [ShapeCollection](../)
* Klasse [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)