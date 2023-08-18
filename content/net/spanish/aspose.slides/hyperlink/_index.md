---
title: Hyperlink
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un hipervínculo.
type: docs
weight: 4640
url: /es/aspose.slides/hyperlink/
---
## Hyperlink class

Representa un hipervínculo.

```csharp
public class Hyperlink : PVIObject, IHyperlink
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crea una instancia de un hipervínculo que apunta a una diapositiva específica. Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación; de lo contrario, el vínculo se guardará como Sin acción. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crea una instancia de un hipervínculo. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crea una instancia de un hipervínculo usando otro hipervínculo como fuente, anulando las propiedades secundarias. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Devuelve un hipervínculo que finaliza el programa. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Devuelve un hipervínculo a la primera diapositiva de la presentación. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Devuelve un hipervínculo a la última diapositiva de la presentación. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Devuelve un hipervínculo a la última diapositiva vista. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Devuelve un hipervínculo especial "reproducir archivo multimedia". Usado en AudioFrame y VideoFrame. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Devuelve un hipervínculo a la siguiente diapositiva. Solo lectura[`Hyperlink`](../hyperlink) . |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Devuelve un hipervínculo especial "no hacer nada". Solo lectura[`Hyperlink`](../hyperlink) . |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Devuelve un hipervínculo a la diapositiva anterior. Solo lectura[`Hyperlink`](../hyperlink) . |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Devuelve el tipo de acción del Hipervínculo. Solo lectura[`HyperlinkActionType`](../hyperlinkactiontype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPPresentationComponent. Solo lectura[`IPresentationComponent`](../ipresentationcomponent) . |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Representa la fuente del color del hipervínculo, ya sea estilos o formato de porción. Lectura/escritura[`HyperlinkColorSource`](../hyperlinkcolorsource) . |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Especifica la URL externa. Solo lecturaString . |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escrituraBoolean . |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina si el objetivo del hipervínculo principal se agregará a una lista de hipervínculos vistos cuando se invoque. Lectura/escrituraBoolean . |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina si el sonido debe detenerse al hacer clic en un hipervínculo. Lectura/escrituraBoolean . |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Devuelve el marco dentro del conjunto de marcos HTML principal para el objetivo del hipervínculo principal cuando existe uno. Leer/escribirString . |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Si el hipervínculo apunta a una diapositiva específica, devuelve esta diapositiva. Solo lectura[`ISlide`](../islide) . |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Devuelve la cadena que puede aparecer en una interfaz de usuario asociada con el hipervínculo principal. Lectura/escrituraString . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina si las dos instancias de Hipervínculo son iguales. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina si las dos instancias de Hipervínculo son iguales. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Sirve como una función hash para un tipo particular, adecuada para usar en algoritmos hash y estructuras de datos como una tabla hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Prueba la igualdad de dos hipervínculos. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Prueba la desigualdad de dos hipervínculos. |

### Ver también

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
