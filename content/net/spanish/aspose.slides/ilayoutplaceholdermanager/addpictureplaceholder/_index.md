---
title: AddPicturePlaceholder
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen.
type: docs
weight: 50
url: /es/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---

## ILayoutPlaceholderManager.AddPicturePlaceholder método

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una imagen.

```csharp
public IAutoShape AddPicturePlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de retorno

Crea un [`IAutoShape`](../../iautoshape) con un marcador de posición de imagen.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de imagen a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddPicturePlaceholder(20, 20, 200, 200);
}
```

### Ver también

* interfaz [IAutoShape](../../iautoshape)
* interfaz [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* espacio de nombres [Aspose.Slides](../../ilayoutplaceholdermanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->