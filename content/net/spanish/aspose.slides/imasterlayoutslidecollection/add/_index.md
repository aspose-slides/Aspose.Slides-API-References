---
title: Add
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agrega una nueva diapositiva de diseño al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection.Add method

Agrega una nueva diapositiva de diseño al final de la colección.

```csharp
public ILayoutSlide Add(SlideLayoutType layoutType, string layoutName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| layoutType | SlideLayoutType | Tipo de diseño para un nuevo diseño. Tipos de diseño admitidos: Título, Solo título, En blanco, Título y objeto, Texto vertical, Título y texto vertical, Dos objetos, Encabezado de sección, Dos textos y dos objetos, Objeto de título y Título, Imagen y Título, Personalizado. Ahora no se admiten otros tipos de diseño: Texto, Texto de dos columnas, Tabla, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject_xObject. |
| layoutName | String | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso, se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente con respecto al tipo de diseño pasado (por ejemplo, "Título de diapositiva" o "1_Título de diapositiva", "2_...", etc. .). |

### Valor_devuelto

Diapositiva añadida.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | Lanzado si el valor del parámetro no es compatible*layoutType* esta pasado. Tipos de diseño que no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentException | Lanzado si el valor del nombre del diseño*layoutName*ya está en uso en esta colección de diseños. |

### Observaciones

1) Diseño agregado para el valor SlideLayoutType.Custom de*layoutType* no contiene marcadores de posición ni formas. 2) Análogo de este método es el método [`Add`](../../igloballayoutslidecollection/add) accedido con[`LayoutSlides`](../../ipresentation/layoutslides) propiedad.

### Ver también

* interface [ILayoutSlide](../../ilayoutslide)
* enum [SlideLayoutType](../../slidelayouttype)
* interface [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../imasterlayoutslidecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
