---
title: AddSmartArt()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un diagrama SmartArt y lo agrega al final de la colección de formas.
type: docs
weight: 79
url: /es/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) método

Crea un diagrama [SmartArt](../../../aspose.slides.smartart/) y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
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
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)