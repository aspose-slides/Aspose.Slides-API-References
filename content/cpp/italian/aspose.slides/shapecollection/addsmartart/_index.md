---
title: AddSmartArt()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 79
url: /it/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metodo

Crea un diagramma [SmartArt](../../../aspose.slides.smartart/) e lo aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del riquadro del diagramma, in punti. |
| y | **float** | La coordinata y del riquadro del diagramma, in punti. |
| width | **float** | La larghezza del riquadro del diagramma, in punti. |
| height | **float** | L'altezza del riquadro del diagramma, in punti. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Il tipo di layout [SmartArt](../../../aspose.slides.smartart/). |

### Valore di ritorno

Il [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) appena creato.
## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```


## Vedi anche

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)