---
title: AddSmartArtPlaceholder
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama SmartArt.
type: docs
weight: 60
url: /es/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---

## ILayoutPlaceholderManager.AddSmartArtPlaceholder método

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener un diagrama SmartArt.

```csharp
public IAutoShape AddSmartArtPlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de Retorno

[`IAutoShape`](../../iautoshape) creado con un marcador de posición SmartArt.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición SmartArt a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddSmartArtPlaceholder(20, 20, 200, 200);
}
```

### Véase También

* interfaz [IAutoShape](../../iautoshape)
* interfaz [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* espacio de nombres [Aspose.Slides](../../ilayoutplaceholdermanager)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->