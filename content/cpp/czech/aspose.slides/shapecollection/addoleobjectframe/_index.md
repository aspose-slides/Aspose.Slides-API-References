---
title: AddOleObjectFrame()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří nový rám OLE objektu a přidá jej na konec kolekce tvarů.
type: docs
weight: 183
url: /cs/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Vytvoří nový rám OLE objektu a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového OLE rámu v bodech. |
| y | **float** | Y-souřadnice nového OLE rámu v bodech. |
| width | **float** | Šířka nového OLE rámu v bodech. |
| height | **float** | Výška nového OLE rámu v bodech. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Návratová hodnota

Nově vytvořený [IOleObjectFrame](../../ioleobjectframe/).

## Poznámky

Následující příklady ukazují, jak přidávat OLE Object Frames do [Slides](../../) PowerPointu [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Přistupuje k prvnímu snímku
auto slide = pres->get_Slides()->idx_get(0);
// Načte soubor Excel do proudu
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

// Vytvoří datový objekt pro vložení
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Přidá tvar Ole Object Frame
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//Zapíše soubor PPTX na disk
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

Vytvoří nový rám OLE objektu a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového OLE rámu v bodech. |
| y | **float** | Y-souřadnice nového OLE rámu v bodech. |
| width | **float** | Šířka nového OLE rámu v bodech. |
| height | **float** | Výška nového OLE rámu v bodech. |
| className | [System::String](../../../system/string/) | Název třídy OLE objektu. |
| path | [System::String](../../../system/string/) | Cesta k propojenému souboru. |

### Návratová hodnota

Nově vytvořený [IOleObjectFrame](../../ioleobjectframe/).

## Poznámky

Tato cesta je v prezentaci uložena doslovně. Pokud je zadána relativní cesta, soubor bude při otevření prezentace z jiného adresáře nedostupný.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOleObjectFrame](../../ioleobjectframe/)
* Třída [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Třída [ShapeCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)