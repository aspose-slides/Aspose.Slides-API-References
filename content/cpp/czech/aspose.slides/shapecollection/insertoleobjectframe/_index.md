---
title: InsertOleObjectFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 196
url: /cs/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově indexovaný index, na který se má vložit rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Návratová hodnota

Nově vytvořený [IOleObjectFrame](../../ioleobjectframe/).
## Poznámky



Tento příklad ukazuje vložení OLE objektu na druhý index: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method


Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově indexovaný index, na který se má vložit rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| className | [System::String](../../../system/string/) | Název třídy OLE objektu. |
| path | [System::String](../../../system/string/) | Cesta k odkazovanému souboru. |

### Návratová hodnota

Nově vytvořený rámec OLE objektu.
## Poznámky



Tato cesta je uložena doslovně v prezentaci. Pokud je zadána relativní cesta, soubor bude nedostupný při otevírání prezentace z jiného adresáře.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOleObjectFrame](../../ioleobjectframe/)
* Třída [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Třída [ShapeCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)