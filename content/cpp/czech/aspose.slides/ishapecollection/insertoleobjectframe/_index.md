---
title: InsertOleObjectFrame()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří nový rám OLE objektu a vloží jej do kolekce tvarů na určeném indexu.
type: docs
weight: 79
url: /cs/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda


Vytvoří nový rám OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | The embedded OLE data information ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Návratová hodnota

The newly created [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metoda


Vytvoří nový rám OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the OLE object frame. |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| className | [System::String](../../../system/string/) | The class name of the OLE object. |
| path | [System::String](../../../system/string/) | The path to the linked file. |

### Návratová hodnota

The newly created [IOleObjectFrame](../../ioleobjectframe/).

## Poznámky



Tato cesta je v prezentaci uložena přesně tak, jak je. Pokud je zadána relativní cesta, soubor bude při otevření prezentace z jiného adresáře nedostupný.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOleObjectFrame](../../ioleobjectframe/)
* Třída [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Třída [IShapeCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)