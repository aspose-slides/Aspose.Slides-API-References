---
title: InsertZoomFrame
second_title: Referencia de la API de Aspose.Slides para .NET
description: Crea un nuevo objeto Zoom y lo inserta en una colección en el índice especificado.
type: docs
weight: 360
url: /es/net/aspose.slides/ishapecollection/insertzoomframe/
---
## InsertZoomFrame(int, float, float, float, float, ISlide) {#insertzoomframe}

Crea un nuevo objeto Zoom y lo inserta en una colección en el índice especificado.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar el marco de Zoom. |
| x | Single | Coordenada X de un nuevo marco de ZoomSingle. |
| y | Single | Coordenada Y de un nuevo marco de ZoomSingle. |
| width | Single | Ancho de un nuevo marco de ZoomSingle. |
| height | Single | Altura de un nuevo marco de ZoomSingle. |
| slide | ISlide | El objeto de diapositiva al que hace referencia el cuadro Zoom[`ISlide`](../../islide). |

### Valor_devuelto

Objeto Zoom creado[`IZoomFrame`](../../izoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La diapositiva a la que se hace referencia no pertenece a la presentación actual. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Zoom en el índice especificado de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentación.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1]);
}
```

### Ver también

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* asamblea [Aspose.Slides](../../../)

---

## InsertZoomFrame(int, float, float, float, float, ISlide, IPPImage) {#insertzoomframe_1}

Crea un nuevo objeto Zoom y lo inserta en una colección en el índice especificado.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide, IPPImage image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar el marco de Zoom. |
| x | Single | Coordenada X de un nuevo marco de ZoomSingle. |
| y | Single | Coordenada Y de un nuevo marco de ZoomSingle. |
| width | Single | Ancho de un nuevo marco de ZoomSingle. |
| height | Single | Altura de un nuevo marco de ZoomSingle. |
| slide | ISlide | El objeto de diapositiva al que hace referencia el cuadro Zoom[`ISlide`](../../islide). |
| image | IPPImage | La imagen de la diapositiva a la que se hace referencia[`IPPImage`](../../ippimage) |

### Valor_devuelto

Objeto Zoom creado[`IZoomFrame`](../../izoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La diapositiva a la que se hace referencia no pertenece a la presentación actual. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Zoom en el índice especificado de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentación.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1], image);
}
```

### Ver también

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->