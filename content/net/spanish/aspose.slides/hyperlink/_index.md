---
title: Hyperlink
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa un hipervínculo.
type: docs
weight: 5120
url: /es/aspose.slides/hyperlink/
---
## Hyperlink clase

Representa un hipervínculo.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crea una instancia de un hipervínculo que apunta a una diapositiva específica. Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación, de lo contrario el vínculo se guardará como NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crea una instancia de un hipervínculo. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crea una instancia de un hipervínculo usando otro hipervínculo como fuente, sobrescribiendo propiedades secundarias. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Devuelve un hipervínculo que finaliza la presentación. Solo lectura [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Devuelve un hipervínculo a la primera diapositiva de la presentación. Solo lectura [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Devuelve un hipervínculo a la última diapositiva de la presentación. Solo lectura [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Devuelve un hipervínculo a la última diapositiva vista. Solo lectura [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Devuelve un hipervínculo especial "reproducir archivo multimedia". Se usa en AudioFrame y VideoFrame. Solo lectura [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Devuelve un hipervínculo a la diapositiva siguiente. Solo lectura [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Devuelve un hipervínculo especial "no hacer nada". Solo lectura [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Devuelve un hipervínculo a la diapositiva anterior. Solo lectura [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Devuelve el tipo de acción del Hipervínculo. Solo lectura [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representa el origen del color del hipervínculo: estilos o formato de porción. Lectura/escritura [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Especifica la URL externa. Solo lectura String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Representa un hipervínculo establecido para esta porción sin tener en cuenta el contenido real de la porción. PowerPoint se comporta de forma específica con los enlaces y su texto correspondiente en una porción. Permite crear texto para el hipervínculo en forma de una URL válida, diferente de la dirección real del enlace. En este caso, al ver el enlace en la ventana de edición, se cambiará para que coincida con la porción de texto. Esta propiedad representa el valor original del hipervínculo. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escritura Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina si el destino del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. Lectura/escritura Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Representa el sonido reproducido por el hipervínculo. Lectura/escritura [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. Lectura/escritura Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Devuelve el marco dentro del conjunto de marcos HTML padre para el destino del hipervínculo padre cuando existe. Lectura/escritura String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si el Hipervínculo apunta a una diapositiva específica, devuelve esa diapositiva. Solo lectura [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Devuelve la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina si las dos instancias de Hyperlink son iguales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina si las dos instancias de Hyperlink son iguales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Funciona como una función hash para un tipo particular, adecuada para su uso en algoritmos de hashing y estructuras de datos como una tabla hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Prueba dos hipervínculos para igualdad. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Prueba dos hipervínculos para desigualdad. |

### Ver también

* clase [PVIObject](../pviobject)
* interfaz [IHyperlink](../ihyperlink)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->