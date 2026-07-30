---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří nový rámec Summary Zoom a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 170
url: /cs/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metoda


Vytvoří nový rámec Summary Zoom a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit rámec Summary Zoom. |
| x | **float** | X-souřadnice nového rámce Summary Zoom, v bodech. |
| y | **float** | Y-souřadnice nového rámce Summary Zoom, v bodech. |
| width | **float** | Šířka nového rámce Summary Zoom, v bodech. |
| height | **float** | Výška nového rámce Summary Zoom, v bodech. |

### Návratová hodnota

Nově vytvořený [ISummaryZoomFrame](../../isummaryzoomframe/).
## Poznámky


Tato metoda vytváří rámec Summary Zoom, který shromažďuje odkazy souhrnu pro všechny sekce v prezentaci. 

Tento příklad ukazuje vytvoření a vložení objektu Summary Zoom na zadaném indexu kolekce (předpokládejme, že v prezentaci "Presentation.pptx" jsou alespoň dvě sekce): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomFrame](../../isummaryzoomframe/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)