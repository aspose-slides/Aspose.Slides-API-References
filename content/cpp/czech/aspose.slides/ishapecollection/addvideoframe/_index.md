---
title: AddVideoFrame()
second_title: Aspose.Slides pro C++ - Reference API
description: Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.
type: docs
weight: 170
url: /cs/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) metoda


Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového video rámce, v bodech. |
| y | **float** | Y-souřadnice nového video rámce, v bodech. |
| width | **float** | Šířka nového video rámce, v bodech. |
| height | **float** | Výška nového video rámce, v bodech. |
| fname | [System::String](../../../system/string/) | Cesta nebo název video souboru, který se má vložit. |

### Návratová hodnota

Nově vytvořený [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metoda


Vytvoří nový video rámec a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového video rámce, v bodech. |
| y | **float** | Y-souřadnice nového video rámce, v bodech. |
| width | **float** | Šířka nového video rámce, v bodech. |
| height | **float** | Výška nového video rámce, v bodech. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) k vložení do video rámce. |

### Návratová hodnota

Nově vytvořený [IVideoFrame](../../ivideoframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IVideoFrame](../../ivideoframe/)
* Třída [String](../../../system/string/)
* Třída [IShapeCollection](../)
* Třída [IVideo](../../ivideo/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)