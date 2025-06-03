---
title: Add
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva diapositiva de diseño a la presentación.
type: docs
weight: 10
url: /es/aspose.slides/globallayoutslidecollection/add/
---

## GlobalLayoutSlideCollection.Add método

Agrega una nueva diapositiva de diseño a la presentación.

```csharp
public ILayoutSlide Add(IMasterSlide master, SlideLayoutType layoutType, string layoutName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | IMasterSlide | Diapositiva maestra para un nuevo diseño. |
| layoutType | SlideLayoutType | Tipo de diseño para un nuevo diseño. Tipos de diseño admitidos: Título, SoloTítulo, Vacío, TítuloYObjeto, TextoVertical, TítuloYTextoVertical, DosObjetos, EncabezadoDeSección, DosTextoYDOSObjetos, TítuloObjetoYSubtítulo, ImagenYSubtítulo, Personalizado. Otros tipos de diseño no son compatibles actualmente: Texto, TextoEnDosColumnas, Tabla, TextoYGráfico, GráficoYTexto, Diagrama, Gráfico, TextoYClipArt, ClipArtYTexto, TextoYObjeto, ObjetoYTexto, Objeto, TextoYMedios, MediosYTexto, ObjetoSobreTexto, TextoSobreObjeto, TextoYDOSObjetos, DosObjetosYTexto, DosObjetosSobreTexto, CuatroObjetos, ClipArtYTextoVertical, TítuloVerticalYTextoSobreGráfico, ObjetoYDOSObjetos, DosObjetosYObjeto. |
| layoutName | String | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso, se lanzará una ArgumentException. Si se pasa un parámetro nulo, entonces se generará automáticamente un nombre en función del tipo de diseño pasado (por ejemplo, "Diapositiva de Título" o "1_Diapositiva de Título", "2_..", etc.). |

### Valor de Retorno

Diapositiva agregada.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | Lanzada si se pasa un valor no compatible para el parámetro *layoutType*. Tipos de diseño que no son compatibles actualmente: Texto, TextoEnDosColumnas, Tabla, TextoYGráfico, GráficoYTexto, Diagrama, Gráfico, TextoYClipArt, ClipArtYTexto, TextoYObjeto, ObjetoYTexto, Objeto, TextoYMedios, MediosYTexto, ObjetoSobreTexto, TextoSobreObjeto, TextoYDOSObjetos, DosObjetosYTexto, DosObjetosSobreTexto, CuatroObjetos, ClipArtYTextoVertical, TítuloVerticalYTextoSobreGráfico, ObjetoYDOSObjetos, DosObjetosYObjeto. |
| ArgumentNullException | Lanzada si *master* es nulo. |
| ArgumentException | Lanzada si *master* pertenece a otra presentación. |
| ArgumentException | Lanzada si el valor del nombre de diseño *layoutName* ya está en uso en la colección de diseños de *master*. |

### Observaciones

1) El diseño agregado para el valor SlideLayoutType.Custom de *layoutType* no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [`Add`](../../imasterlayoutslidecollection/add) accesible con la propiedad [`LayoutSlides`](../../imasterslide/layoutslides).

### Véase También

* interfaz [ILayoutSlide](../../ilayoutslide)
* interfaz [IMasterSlide](../../imasterslide)
* enum [SlideLayoutType](../../slidelayouttype)
* clase [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../globallayoutslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->