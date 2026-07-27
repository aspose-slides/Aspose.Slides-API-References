---
title: AddOnlineImagePlaceholder()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen en línea.
type: docs
weight: 118
url: /es/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) método

Agrega una nueva forma de marcador de posición al diseño de la diapositiva para contener una imagen en línea.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | La altura de la nueva forma de marcador de posición. |

### Valor de retorno

Se creó [IAutoShape](../../iautoshape/) con un marcador de posición de Imagen en línea.

## Observaciones

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Imagen en línea al diseño de la diapositiva. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [LayoutPlaceholderManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)