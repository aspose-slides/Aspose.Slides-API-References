---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů.
type: docs
weight: 144
url: /cs/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metoda


Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového rámce Summary Zoom v bodech. |
| y | **float** | Y-souřadnice nového rámce Summary Zoom v bodech. |
| width | **float** | Šířka nového rámce Summary Zoom v bodech. |
| height | **float** | Výška nového rámce Summary Zoom v bodech. |

### Návratová hodnota

Nově vytvořený [ISummaryZoomFrame](../../isummaryzoomframe/).

## Poznámky


Tato metoda vytváří rámec Summary Zoom, který shromažďuje souhrnné odkazy pro všechny sekce v prezentaci. 

Tento příklad ukazuje, jak přidat objekt Summary Zoom na konec kolekce (předpokládejme, že v prezentaci \"Presentation.pptx\" existují alespoň dvě sekce): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomFrame](../../isummaryzoomframe/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)