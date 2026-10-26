---
title: AddTablePlaceholder()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición al diseño de la diapositiva para contener una tabla.
type: docs
weight: 79
url: /es/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) método

Agrega una nueva forma de marcador de posición al diseño de la diapositiva para contener una tabla.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | El alto de la nueva forma de marcador de posición. |

### Valor devuelto

Creado [IAutoShape](../../iautoshape/) con un marcador de posición [Table](../../table/).

## Observaciones

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición [Table](../../table/) al diseño de la diapositiva. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [ILayoutPlaceholderManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)