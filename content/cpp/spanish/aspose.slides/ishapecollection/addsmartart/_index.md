---
title: AddSmartArt()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un diagrama SmartArt y lo agrega al final de la colección de formas.
type: docs
weight: 40
url: /es/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) método

Crea un [SmartArt](../../../aspose.slides.smartart/) diagrama y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del marco del diagrama, en puntos. |
| y | **float** | La coordenada y del marco del diagrama, en puntos. |
| width | **float** | El ancho del marco del diagrama, en puntos. |
| height | **float** | La altura del marco del diagrama, en puntos. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | El tipo de diseño [SmartArt](../../../aspose.slides.smartart/). |

### Valor de retorno

El [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) recién creado.

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Ver también

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)