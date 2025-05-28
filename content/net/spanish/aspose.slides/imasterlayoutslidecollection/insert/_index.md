---
title: Insertar
second_title: Referencia de API de Aspose.Slides para .NET
description: Inserta una nueva diapositiva de diseño en la posición especificada de la colección.
type: docs
weight: 40
url: /es/aspose.slides/imasterlayoutslidecollection/insert/
---

## Método IMasterLayoutSlideCollection.Insert

Inserta una nueva diapositiva de diseño en la posición especificada de la colección.

```csharp
public ILayoutSlide Insert(int index, SlideLayoutType layoutType, string layoutName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| layoutType | SlideLayoutType | Tipo de diseño para un nuevo diseño. Tipos de diseño soportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son soportados actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso, se lanzará una ArgumentException. Si se pasa un parámetro null, el nombre se generará automáticamente en relación con el tipo de diseño pasado (por ejemplo, "Title Slide" o "1_Title Slide", "2_..", etc.). |

### Valor de retorno

Diapositiva insertada.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | Lanzada si se pasa un valor no soportado del parámetro *layoutType*. Tipos de diseño que no son soportados actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentException | Lanzada si el valor del nombre de diseño *layoutName* ya está en uso en esta colección de diseños. |

### Observaciones

El diseño insertado para el valor SlideLayoutType.Custom de *layoutType* no contiene marcadores de posición ni formas.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* enum [SlideLayoutType](../../slidelayouttype)
* interfaz [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../imasterlayoutslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->