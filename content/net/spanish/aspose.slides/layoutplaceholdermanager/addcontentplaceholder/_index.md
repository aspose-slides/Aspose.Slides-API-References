---
title: AgregarContenidoMarcador
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva forma de marcador al diseño de la diapositiva para contener contenido como una imagen, tabla, medio o texto.
type: docs
weight: 20
url: /es/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---

## LayoutPlaceholderManager.AddContentPlaceholder método

Agrega una nueva forma de marcador a la diapositiva de diseño para contener contenido, como una imagen, tabla, medio o texto.

```csharp
public IAutoShape AddContentPlaceholder(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | La coordenada X de la nueva forma de marcador. |
| y | Single | La coordenada Y de la nueva forma de marcador. |
| width | Single | El ancho de la nueva forma de marcador. |
| height | Single | La altura de la nueva forma de marcador. |

### Valor de Retorno

Crea un [`IAutoShape`](../../iautoshape) con un marcador de Contenido.

### Ejemplos

El siguiente ejemplo muestra cómo agregar la forma de marcador de Contenido a la diapositiva de diseño.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddContentPlaceholder(20, 20, 500, 300);
}
```

### Véase También

* interfaz [IAutoShape](../../iautoshape)
* clase [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* espacio de nombres [Aspose.Slides](../../layoutplaceholdermanager)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->