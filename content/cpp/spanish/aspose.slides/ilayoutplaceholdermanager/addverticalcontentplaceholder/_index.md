---
title: AddVerticalContentPlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición a la diapositiva del diseño para contener contenido, como una imagen, tabla, medio o texto en dirección vertical.
type: docs
weight: 14
url: /es/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) método

Agrega una nueva forma de marcador de posición al diseño de diapositiva para contener contenido, como una imagen, tabla, medio o texto en dirección vertical.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | La altura de la nueva forma de marcador de posición. |

### Valor devuelto

Creado [IAutoShape](../../iautoshape/) con un marcador de contenido (vertical).

## Observaciones

El siguiente ejemplo muestra cómo agregar la forma de marcador de contenido (vertical) a la diapositiva de diseño. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)