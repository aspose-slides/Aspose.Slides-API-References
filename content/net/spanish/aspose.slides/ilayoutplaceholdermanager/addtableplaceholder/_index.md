---
title: AddTablePlaceholder
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una tabla.
type: docs
weight: 70
url: /es/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---

## Método ILayoutPlaceholderManager.AddTablePlaceholder

Agrega una nueva forma de marcador de posición a la diapositiva de diseño para contener una tabla.

```csharp
public IAutoShape AddTablePlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador de posición. |
| y | Single | La coordenada Y de la nueva forma de marcador de posición. |
| width | Single | El ancho de la nueva forma de marcador de posición. |
| height | Single | La altura de la nueva forma de marcador de posición. |

### Valor de Retorno

Crea un [`IAutoShape`](../../iautoshape) con un marcador de posición de tabla.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de posición de Tabla a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddTablePlaceholder(20, 20, 500, 200);
}
```

### Véase También

* interfaz [IAutoShape](../../iautoshape)
* interfaz [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* espacio de nombres [Aspose.Slides](../../ilayoutplaceholdermanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->