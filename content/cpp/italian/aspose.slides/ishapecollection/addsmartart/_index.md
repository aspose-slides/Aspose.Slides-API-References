---
title: AddSmartArt()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 40
url: /it/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metodo

Crea un diagramma [SmartArt](../../../aspose.slides.smartart/) e lo aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del riquadro del diagramma, in punti. |
| y | **float** | La coordinata y del riquadro del diagramma, in punti. |
| width | **float** | La larghezza del riquadro del diagramma, in punti. |
| height | **float** | L’altezza del riquadro del diagramma, in punti. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Il tipo di layout [SmartArt](../../../aspose.slides.smartart/). |

### Valore restituito

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
* Classe [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)