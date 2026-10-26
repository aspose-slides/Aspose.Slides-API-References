---
title: AddOleObjectFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny OLE-objektram och lägger till den i slutet av shape-samlingen.
type: docs
weight: 183
url: /sv/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metod

Skapar en ny OLE-objekt-ram och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | Den x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Den y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Information om den inbäddade OLE-datan ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).
## Anmärkningar

Följande exempel visar hur man lägger till OLE-objekt-ramar till [Slides](../../) i PowerPoint [Presentation](../../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>();

// Hämtar den första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Laddar en Excel-fil till en ström
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

// Skapar ett dataobjekt för inbäddning
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Lägger till en OLE-objektram
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//Skriver PPTX-filen till disk
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metod

Skapar en ny OLE-objekt-ram och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | Den x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Den y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| className | [System::String](../../../system/string/) | Klassnamnet för OLE-objektet. |
| path | [System::String](../../../system/string/) | Sökvägen till den länkade filen. |

### Returvärde

Den nyss skapade [IOleObjectFrame](../../ioleobjectframe/).
## Anmärkningar

Denna sökväg lagras exakt som den är i presentationen. Om en relativ sökväg anges blir filen oåtkomlig när presentationen öppnas från en annan katalog.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOleObjectFrame](../../ioleobjectframe/)
* Klass [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klass [ShapeCollection](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)