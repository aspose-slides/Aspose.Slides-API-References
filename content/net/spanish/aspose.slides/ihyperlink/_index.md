---
title: IHyperlink
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un hiperenlace.
type: docs
weight: 5910
url: /es/aspose.slides/ihyperlink/
---

## Interfaz IHyperlink

Representa un hiperenlace.

```csharp
public interface IHyperlink
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActionType](../../aspose.slides/ihyperlink/actiontype) { get; } | Devuelve el tipo de acción de HyperLinkEx. Solo lectura [`HyperlinkActionType`](../hyperlinkactiontype). |
| [ColorSource](../../aspose.slides/ihyperlink/colorsource) { get; set; } | Representa la fuente del color del hiperenlace, ya sea estilos o formato de porción. Lectura/escritura [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/ihyperlink/externalurl) { get; } | Especifica la URL externa. Si esta propiedad no es nula, entonces la propiedad TargetSlide se vuelve nula. Solo lectura String. |
| [ExternalUrlOriginal](../../aspose.slides/ihyperlink/externalurloriginal) { get; } | Representa un hiperenlace que se establece para esta porción sin considerar el contenido real de la porción. PowerPoint se comporta específicamente para enlaces y su texto correspondiente en una porción. Permite crear texto para el hiperenlace en forma de una URL válida, diferente de la dirección real del enlace. En este caso, al ver el enlace en la ventana de edición, se cambiará para que coincida con el texto de la porción. Esta propiedad representa el valor original del hiperenlace. |
| [HighlightClick](../../aspose.slides/ihyperlink/highlightclick) { get; set; } | Determina si el hiperenlace debe destacarse al hacer clic. Lectura/escritura Boolean. |
| [History](../../aspose.slides/ihyperlink/history) { get; set; } | Determina si el objetivo del hiperenlace principal debe ser agregado a una lista de hiperenlaces vistos cuando se invoca. Lectura/escritura Boolean. |
| [Sound](../../aspose.slides/ihyperlink/sound) { get; set; } | Representa el sonido que se reproduce del hiperenlace. Lectura/escritura [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/ihyperlink/stopsoundonclick) { get; set; } | Determina si el sonido debe detenerse al hacer clic en el hiperenlace. Lectura/escritura Boolean. |
| [TargetFrame](../../aspose.slides/ihyperlink/targetframe) { get; set; } | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hiperenlace principal cuando existe uno. Lectura/escritura String. |
| [TargetSlide](../../aspose.slides/ihyperlink/targetslide) { get; } | Si el HyperlinkEx apunta a una diapositiva específica, devuelve esta diapositiva. Si la propiedad no es nula, entonces la propiedad ExternalUrl se vuelve nula. Solo lectura [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/ihyperlink/tooltip) { get; set; } | Devuelve la cadena que puede mostrarse en una interfaz de usuario como asociada con el hiperenlace principal. Lectura/escritura String. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.slides/ihyperlink/equals)(IHyperlink) | Determina si las dos instancias de Hiperenlace son iguales. |

### Véase también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->