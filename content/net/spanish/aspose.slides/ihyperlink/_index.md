---
title: IHyperlink
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un hipervínculo.
type: docs
weight: 5570
url: /es/aspose.slides/ihyperlink/
---
## IHyperlink interface

Representa un hipervínculo.

```csharp
public interface IHyperlink
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActionType](../../aspose.slides/ihyperlink/actiontype) { get; } | Devuelve el tipo de acción de HyperLinkEx. Solo lectura[`HyperlinkActionType`](../hyperlinkactiontype) . |
| [ColorSource](../../aspose.slides/ihyperlink/colorsource) { get; set; } | Representa la fuente del color del hipervínculo, ya sea estilos o formato de porción. Lectura/escritura[`HyperlinkColorSource`](../hyperlinkcolorsource) . |
| [ExternalUrl](../../aspose.slides/ihyperlink/externalurl) { get; } | Especifica la URL externa Si esta propiedad deja de ser nula, entonces la propiedad TargetSlide se vuelve nula. Solo lecturaString . |
| [HighlightClick](../../aspose.slides/ihyperlink/highlightclick) { get; set; } | Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escrituraBoolean . |
| [History](../../aspose.slides/ihyperlink/history) { get; set; } | Determina si el objetivo del hipervínculo principal se agregará a una lista de hipervínculos vistos cuando se invoque. Lectura/escrituraBoolean . |
| [StopSoundOnClick](../../aspose.slides/ihyperlink/stopsoundonclick) { get; set; } | Determina si el sonido debe detenerse al hacer clic en un hipervínculo. Lectura/escrituraBoolean . |
| [TargetFrame](../../aspose.slides/ihyperlink/targetframe) { get; set; } | Devuelve el marco dentro del conjunto de marcos HTML principal para el destino del hipervínculo principal cuando existe. Lectura/escrituraString . |
| [TargetSlide](../../aspose.slides/ihyperlink/targetslide) { get; } | Si HyperlinkEx apunta a una diapositiva específica, devuelve esta diapositiva. Si la propiedad no se vuelve nula, entonces la propiedad ExternalUrl se vuelve nula. Solo lectura[`ISlide`](../islide) . |
| [Tooltip](../../aspose.slides/ihyperlink/tooltip) { get; set; } | Devuelve la cadena que puede aparecer en una interfaz de usuario asociada con el hipervínculo principal. Lectura/escrituraString . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.slides/ihyperlink/equals)(IHyperlink) | Determina si las dos instancias de Hipervínculo son iguales. |

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
