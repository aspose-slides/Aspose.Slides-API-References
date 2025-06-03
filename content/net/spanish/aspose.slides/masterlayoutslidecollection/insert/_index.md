---
title: Insert
second_title: Referencia de API de Aspose.Slides para .NET
description: Inserta una nueva diapositiva de diseño en la posición especificada de la colección.
type: docs
weight: 30
url: /es/aspose.slides/masterlayoutslidecollection/insert/
---

## Método MasterLayoutSlideCollection.Insert

Inserta una nueva diapositiva de diseño en la posición especificada de la colección.

```csharp
public ILayoutSlide Insert(int index, SlideLayoutType layoutType, string layoutName)
```

| Parámetro  | Tipo      | Descripción  |
| ---        | ---       | ---          |
| index      | Int32     | Índice de la nueva diapositiva. |
| layoutType | SlideLayoutType | Tipo de diseño para una nueva diapositiva de diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String    | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso, se lanzará una ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en relación con el tipo de diseño pasado (por ejemplo, "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Valor de Retorno

Diapositiva insertada.

### Excepciones

| excepción                | condición |
| ----------------------- | --- |
| NotImplementedException  | Lanzado si se pasa un valor no compatible para el parámetro *layoutType*. Tipos de diseño que no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentException       | Lanzado si el valor del nombre de diseño *layoutName* ya está en uso en esta colección de diseños. |

### Notas

El diseño insertado para el valor SlideLayoutType.Custom de *layoutType* no contiene marcadores de posición ni formas.

### Ver También

* interfaz [ILayoutSlide](../../ilayoutslide)
* enum [SlideLayoutType](../../slidelayouttype)
* clase [MasterLayoutSlideCollection](../../masterlayoutslidecollection)
* namespace [Aspose.Slides](../../masterlayoutslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->