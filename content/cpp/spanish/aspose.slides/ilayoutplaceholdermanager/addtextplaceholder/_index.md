---
title: AddTextPlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto.
type: docs
weight: 27
url: /es/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) método

Agrega una nueva forma de marcador de posición al diapositiva de diseño para contener contenido de texto.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | La altura de la nueva forma de marcador de posición. |

### Valor devuelto

Creado [IAutoShape](../../iautoshape/) con un marcador de posición de Texto.

## Observaciones

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Texto al diapositiva de diseño. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [ILayoutPlaceholderManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)