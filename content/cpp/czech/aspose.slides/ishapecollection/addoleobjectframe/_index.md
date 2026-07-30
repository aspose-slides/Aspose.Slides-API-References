---
title: AddOleObjectFrame()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.
type: docs
weight: 66
url: /cs/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového OLE rámce v bodech. |
| y | **float** | Y-souřadnice nového OLE rámce v bodech. |
| width | **float** | Šířka nového OLE rámce v bodech. |
| height | **float** | Výška nového OLE rámce v bodech. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informace o vložených OLE datech ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Návratová hodnota

Nově vytvořený [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method


Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového OLE rámce v bodech. |
| y | **float** | Y-souřadnice nového OLE rámce v bodech. |
| width | **float** | Šířka nového OLE rámce v bodech. |
| height | **float** | Výška nového OLE rámce v bodech. |
| className | [System::String](../../../system/string/) | Název třídy OLE objektu. |
| path | [System::String](../../../system/string/) | Cesta k propojenému souboru. |

### Návratová hodnota

Nově vytvořený [IOleObjectFrame](../../ioleobjectframe/).

## Poznámky



Tato cesta je uložena doslovně v prezentaci. Pokud je zadána relativní cesta, soubor bude při otevírání prezentace z jiného adresáře nedostupný.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOleObjectFrame](../../ioleobjectframe/)
* Třída [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Třída [IShapeCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)