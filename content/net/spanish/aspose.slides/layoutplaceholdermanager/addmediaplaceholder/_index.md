---
title: AddMediaPlaceholder
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un objeto multimedia.
type: docs
weight: 30
url: /es/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---

## LayoutPlaceholderManager.AddMediaPlaceholder método

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un objeto multimedia.

```csharp
public IAutoShape AddMediaPlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de retorno

Crea un [`IAutoShape`](../../iautoshape) con un marcador de posición de Multimedia.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Multimedia a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddMediaPlaceholder(20, 20, 200, 200);
}
```

### Véase también

* interfaz [IAutoShape](../../iautoshape)
* clase [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* espacio de nombres [Aspose.Slides](../../layoutplaceholdermanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->