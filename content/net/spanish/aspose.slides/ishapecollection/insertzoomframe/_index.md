---
title: InsertZoomFrame
second_title: Referencia de la API Aspose.Slides para .NET
description: Crea un nuevo objeto Zoom e lo inserta en una colección en el índice especificado.
type: docs
weight: 360
url: /es/aspose.slides/ishapecollection/insertzoomframe/
---

## InsertZoomFrame(int, float, float, float, float, ISlide) {#insertzoomframe}

Crea un nuevo objeto Zoom e lo inserta en una colección en el índice especificado.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco Zoom. |
| x | Single | Coordenada X de un nuevo marco Zoom Single. |
| y | Single | Coordenada Y de un nuevo marco Zoom Single. |
| width | Single | Ancho de un nuevo marco Zoom Single. |
| height | Single | Altura de un nuevo marco Zoom Single. |
| slide | ISlide | El objeto de la diapositiva referenciado por el marco Zoom [`ISlide`](../../islide). |

### Valor de Retorno

Objeto Zoom creado [`IZoomFrame`](../../izoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La diapositiva referenciada no pertenece a la presentación actual. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Zoom en el índice específico de una colección (suponiendo que hay al menos dos diapositivas en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1]);
}
```

### Ver También

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertZoomFrame(int, float, float, float, float, ISlide, IPPImage) {#insertzoomframe_1}

Crea un nuevo objeto Zoom e lo inserta en una colección en el índice especificado.

```csharp
public IZoomFrame InsertZoomFrame(int index, float x, float y, float width, float height, 
    ISlide slide, IPPImage image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco Zoom. |
| x | Single | Coordenada X de un nuevo marco Zoom Single. |
| y | Single | Coordenada Y de un nuevo marco Zoom Single. |
| width | Single | Ancho de un nuevo marco Zoom Single. |
| height | Single | Altura de un nuevo marco Zoom Single. |
| slide | ISlide | El objeto de la diapositiva referenciado por el marco Zoom [`ISlide`](../../islide). |
| image | IPPImage | La imagen para la diapositiva referenciada [`IPPImage`](../../ippimage) |

### Valor de Retorno

Objeto Zoom creado [`IZoomFrame`](../../izoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La diapositiva referenciada no pertenece a la presentación actual. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Zoom en el índice específico de una colección (suponiendo que hay al menos dos diapositivas en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertZoomFrame(2, 150, 20, 50, 50, pres.Slides[1], image);
}
```

### Ver También

* interface [IZoomFrame](../../izoomframe)
* interface [ISlide](../../islide)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->