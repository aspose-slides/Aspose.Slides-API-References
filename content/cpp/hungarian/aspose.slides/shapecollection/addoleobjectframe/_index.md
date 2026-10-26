---
title: AddOleObjectFrame()
second_title: Aspose.Slides C++ API referencia
description: Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 183
url: /hu/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metódus

Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új OLE keret x koordinátája pontban. |
| y | **float** | Az új OLE keret y koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Az beágyazott OLE adatok információi ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## Megjegyzések

A következő példák bemutatják, hogyan lehet OLE objektumkereteket hozzáadni a [Slides](../../)-hoz a PowerPoint [Presentation](../../presentation/)-ben. 
```cpp
auto pres = System::MakeObject<Presentation>();

// Eléri az első diát
auto slide = pres->get_Slides()->idx_get(0);
// Betölti az Excel fájlt egy adatfolyamba
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

// Létrehoz egy adatobjektumot a beágyazáshoz
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Hozzáad egy Ole Object Frame alakzatot
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//A PPTX fájlt lemezre írja
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metódus

Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új OLE keret x koordinátája pontban. |
| y | **float** | Az új OLE keret y koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| className | [System::String](../../../system/string/) | Az OLE objektum osztályneve. |
| path | [System::String](../../../system/string/) | A hivatkozott fájl elérési útja. |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## Megjegyzések

Ez az útvonal pontosan úgy van tárolva a prezentációban. Ha relatív útvonal van megadva, a fájl nem lesz elérhető, amikor a prezentációt egy másik könyvtárból nyitják meg.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleObjectFrame](../../ioleobjectframe/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [ShapeCollection](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)