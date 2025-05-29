---
title: Agregar
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva diapositiva de diseño a la presentación.
type: docs
weight: 20
url: /es/aspose.slides/igloballayoutslidecollection/add/
---

## Método IGlobalLayoutSlideCollection.Add

Agrega una nueva diapositiva de diseño a la presentación.

```csharp
public ILayoutSlide Add(IMasterSlide master, SlideLayoutType layoutType, string layoutName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | IMasterSlide | Diapositiva maestra para un nuevo diseño. |
| layoutType | SlideLayoutType | Tipo de diseño para un nuevo diseño. Tipos de diseño soportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son soportados ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso, se lanzará ArgumentException. Si se pasa un parámetro nulo, entonces el nombre se generará automáticamente en relación al tipo de diseño pasado (por ejemplo, "Título Diapositiva" o "1_Título Diapositiva", "2_..", etc.). |

### Valor de Retorno

Diapositiva agregada.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | Lanzado si se pasa un valor no soportado para el parámetro *layoutType*. Tipos de diseño que no están soportados ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentNullException | Lanzado si *master* es nulo. |
| ArgumentException | Lanzado si *master* pertenece a otra presentación. |
| ArgumentException | Lanzado si el valor del nombre del diseño *layoutName* ya está en uso en la colección de diseños de *master*. |

### Observaciones

1) La diapositiva de diseño agregada para el valor SlideLayoutType.Custom de *layoutType* no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [`Add`](../../imasterlayoutslidecollection/add) accesible con la propiedad [`LayoutSlides`](../../imasterslide/layoutslides).

### Ver También

* interfaz [ILayoutSlide](../../ilayoutslide)
* interfaz [IMasterSlide](../../imasterslide)
* enum [SlideLayoutType](../../slidelayouttype)
* interfaz [IGlobalLayoutSlideCollection](../../igloballayoutslidecollection)
* namespace [Aspose.Slides](../../igloballayoutslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->