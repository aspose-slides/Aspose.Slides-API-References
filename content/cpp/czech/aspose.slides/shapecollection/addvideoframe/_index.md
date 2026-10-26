---
title: AddVideoFrame()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový video rámeček a přidá jej na konec kolekce tvarů.
type: docs
weight: 209
url: /cs/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metoda

Vytvoří nový video rámeček a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice x nového video rámečku, v bodech. |
| y | **float** | Souřadnice y nového video rámečku, v bodech. |
| width | **float** | Šířka nového video rámečku, v bodech. |
| height | **float** | Výška nového video rámečku, v bodech. |
| fname | [System::String](../../../system/string/) | Cesta nebo název video souboru k vložení. |

### Návratová hodnota

Nově vytvořený [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metoda

Vytvoří nový video rámeček a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice x nového video rámečku, v bodech. |
| y | **float** | Souřadnice y nového video rámečku, v bodech. |
| width | **float** | Šířka nového video rámečku, v bodech. |
| height | **float** | Výška nového video rámečku, v bodech. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) k vložení do video rámečku. |

### Návratová hodnota

Nově vytvořený [IVideoFrame](../../ivideoframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IVideoFrame](../../ivideoframe/)
* Třída [String](../../../system/string/)
* Třída [ShapeCollection](../)
* Třída [IVideo](../../ivideo/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)