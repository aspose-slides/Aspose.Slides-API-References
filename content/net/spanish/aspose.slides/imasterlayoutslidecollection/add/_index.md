---
title: Add
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una nueva diapositiva de diseño al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/imasterlayoutslidecollection/add/
---

## IMasterLayoutSlideCollection.Add método

Agrega una nueva diapositiva de diseño al final de la colección.

```csharp
public ILayoutSlide Add(SlideLayoutType layoutType, string layoutName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layoutType | SlideLayoutType | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Título, SoloTítulo, En blanco, TítuloYObjeto, TextoVertical, TítuloYTextoVertical, DosObjetos, EncabezadoDeSección, DosTextosYDosObjetos, ObjetoTítuloYSubtítulo, ImagenYSubtítulo, Personalizado. Otros tipos de diseño no son compatibles en este momento: Texto, TextoADosColumnas, Tabla, TextoYGráfico, GráficoYTexto, Diagrama, Gráfico, TextoYClipArt, ClipArtYTexto, TextoYObjeto, ObjetoYTexto, Objeto, TextoYMedios, MediosYTexto, ObjetoSobreTexto, TextoSobreObjeto, TextoYDosObjetos, DosObjetosYTexto, DosObjetosSobreTexto, CuatroObjetos, ClipArtYTextoVertical, TítuloVerticalYTextoSobreGráfico, ObjetoYDobleObjeto, DosObjetosYObjeto. |
| layoutName | String | Nombre para un nuevo diseño. Si el nombre pasado ya está en uso, se lanzará ArgumentException. Si se pasa un parámetro nulo, entonces el nombre se generará automáticamente en relación al tipo de diseño pasado (por ejemplo, "Diapositiva de Título" o "1_Diapositiva de Título", "2_..", etc.). |

### Valor de Retorno

Diapositiva agregada.

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | Lanzada si se pasa un valor no soportado del parámetro *layoutType*. Tipos de diseño que no son compatibles en este momento: Texto, TextoADosColumnas, Tabla, TextoYGráfico, GráficoYTexto, Diagrama, Gráfico, TextoYClipArt, ClipArtYTexto, TextoYObjeto, ObjetoYTexto, Objeto, TextoYMedios, MediosYTexto, ObjetoSobreTexto, TextoSobreObjeto, TextoYDosObjetos, DosObjetosYTexto, DosObjetosSobreTexto, CuatroObjetos, ClipArtYTextoVertical, TítuloVerticalYTextoSobreGráfico, ObjetoYDobleObjeto, DosObjetosYObjeto. |
| ArgumentException | Lanzada si el valor del nombre del diseño *layoutName* ya está en uso en esta colección de diseños. |

### Observaciones

1) El diseño agregado para el valor SlideLayoutType.Custom de *layoutType* no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [`Add`](../../igloballayoutslidecollection/add) accesible con la propiedad [`LayoutSlides`](../../ipresentation/layoutslides).

### Vea También

* interfaz [ILayoutSlide](../../ilayoutslide)
* enum [SlideLayoutType](../../slidelayouttype)
* interfaz [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* namespace [Aspose.Slides](../../imasterlayoutslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->