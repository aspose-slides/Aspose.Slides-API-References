---
title: AddVerticalContentPlaceholder
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido como una imagen, tabla, medios o texto en dirección vertical.
type: docs
weight: 90
url: /es/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---

## ILayoutPlaceholderManager.AddVerticalContentPlaceholder método

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido, como una imagen, tabla, medios o texto en dirección vertical.

```csharp
public IAutoShape AddVerticalContentPlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de Retorno

Crea un [`IAutoShape`](../../iautoshape) con un marcador de posición de Contenido (Vertical).

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Contenido (Vertical) a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddVerticalContentPlaceholder(20, 20, 300, 500);
}
```

### Ver También

* interfaz [IAutoShape](../../iautoshape)
* interfaz [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->