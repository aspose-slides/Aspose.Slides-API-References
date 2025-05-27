---
title: InsertSectionZoomFrame
second_title: Referencia de la API de Aspose.Slides para .NET
description: Crea un nuevo objeto Section Zoom e inserta en una colección en el índice especificado.
type: docs
weight: 320
url: /es/aspose.slides/ishapecollection/insertsectionzoomframe/
---

## InsertSectionZoomFrame(int, float, float, float, float, ISection) {#insertsectionzoomframe}

Crea un nuevo objeto Section Zoom e inserta en una colección en el índice especificado.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco de sección Zoom. |
| x | Single | Coordenada X de un nuevo marco de sección Zoom Single. |
| y | Single | Coordenada Y de un nuevo marco de sección Zoom Single. |
| width | Single | Ancho de un nuevo marco de sección Zoom Single. |
| height | Single | Altura de un nuevo marco de sección Zoom Single. |
| section | ISection | El objeto de la diapositiva referenciado por el marco de sección Zoom [`ISection`](../../isection). |

### Valor de retorno

Objeto Section Zoom creado [`ISectionZoomFrame`](../../isectionzoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La sección referenciada no pertenece a la presentación actual o no contiene ninguna diapositiva. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1]);
}
```

### Véase también

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertSectionZoomFrame(int, float, float, float, float, ISection, IPPImage) {#insertsectionzoomframe_1}

Crea un nuevo objeto Section Zoom e inserta en una colección en el índice especificado.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section, IPPImage image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco de sección Zoom. |
| x | Single | Coordenada X de un nuevo marco de sección Zoom Single. |
| y | Single | Coordenada Y de un nuevo marco de sección Zoom Single. |
| width | Single | Ancho de un nuevo marco de sección Zoom Single. |
| height | Single | Altura de un nuevo marco de sección Zoom Single. |
| section | ISection | El objeto de la diapositiva referenciado por el marco de sección Zoom [`ISection`](../../isection). |
| image | IPPImage | La imagen para la diapositiva referenciada [`IPPImage`](../../ippimage) |

### Valor de retorno

Objeto Section Zoom creado [`ISectionZoomFrame`](../../isectionzoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La sección referenciada no pertenece a la presentación actual o no contiene ninguna diapositiva. |

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1], image);
}
```

### Véase también

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generado por xmldocmd para Aspose.Slides.dll -->