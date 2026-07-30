---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides pro C++ – Referenční příručka API
description: Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů.
type: docs
weight: 157
url: /cs/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) metoda

Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
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

Tato metoda vytvoří nový Summary Zoom a vloží do něj kolekci objektů pro všechny sekce v této prezentaci. 

Tento příklad ukazuje přidání objektu Summary Zoom na konec kolekce (předpokládejte, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Viz také

* Třída [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomFrame](../../isummaryzoomframe/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)