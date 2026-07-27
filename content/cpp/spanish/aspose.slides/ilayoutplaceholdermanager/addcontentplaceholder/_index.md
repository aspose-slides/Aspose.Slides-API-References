---
title: AddContentPlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva forma placeholder al slide de diseño para contener contenido, como una imagen, tabla, medio o texto.
type: docs
weight: 1
url: /es/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) método

Agrega una nueva forma placeholder al slide de diseño para contener contenido, como una imagen, tabla, medio o texto.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma placeholder. |
| y | **float** | La coordenada Y de la nueva forma placeholder. |
| width | **float** | El ancho de la nueva forma placeholder. |
| height | **float** | La altura de la nueva forma placeholder. |

### Valor devuelto

Creado [IAutoShape](../../iautoshape/) con un Content placeholder.

## Observaciones

El siguiente ejemplo muestra cómo agregar la forma Content placeholder al slide de diseño. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [ILayoutPlaceholderManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)