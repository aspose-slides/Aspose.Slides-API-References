---
title: AddTextPlaceholder
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto.
type: docs
weight: 80
url: /es/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---

## Método ILayoutPlaceholderManager.AddTextPlaceholder

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener contenido de texto.

```csharp
public IAutoShape AddTextPlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de Retorno

[`IAutoShape`](../../iautoshape) creado con un marcador de posición de texto.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de texto a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddTextPlaceholder(20, 20, 500, 300);
}
```

### Ver También

* interfaz [IAutoShape](../../iautoshape)
* interfaz [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->