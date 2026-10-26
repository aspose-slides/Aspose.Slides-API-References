---
title: AddContentPlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición al slide de diseño para contener contenido, como una imagen, tabla, medio o texto.
type: docs
weight: 1
url: /es/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) método


Agrega una nueva forma de marcador de posición al slide de diseño para contener contenido, como una imagen, tabla, medio o texto.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | La altura de la nueva forma de marcador de posición. |

### Valor devuelto

Creado [IAutoShape](../../iautoshape/) con un marcador de posición Content.

## Observaciones



El siguiente ejemplo muestra cómo agregar la forma de marcador de posición Content al slide de diseño. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [LayoutPlaceholderManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)