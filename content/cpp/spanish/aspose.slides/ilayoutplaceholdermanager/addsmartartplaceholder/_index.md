---
title: AddSmartArtPlaceholder()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama SmartArt.
type: docs
weight: 92
url: /es/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method


Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la nueva forma de marcador de posición. |
| y | **float** | La coordenada Y de la nueva forma de marcador de posición. |
| width | **float** | El ancho de la nueva forma de marcador de posición. |
| height | **float** | La altura de la nueva forma de marcador de posición. |

### Valor de retorno

Se creó [IAutoShape](../../iautoshape/) con un marcador de posición [SmartArt](../../../aspose.slides.smartart/).

## Observaciones



El siguiente ejemplo muestra cómo agregar la forma de marcador de posición [SmartArt](../../../aspose.slides.smartart/) a la diapositiva de diseño. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)