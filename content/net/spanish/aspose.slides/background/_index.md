---
title: Fondo
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa el fondo de una diapositiva.
type: docs
weight: 850
url: /es/aspose.slides/background/
---

## Clase Background

Representa el fondo de una diapositiva.

```csharp
public sealed class Background : PVIObject, IBackground
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [EffectFormat](../../aspose.slides/background/effectformat) { get; } | Devuelve un EffectFormat para el relleno de tipo BackgroundType.OwnBackground. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/background/fillformat) { get; } | Devuelve un FillFormat para el relleno de tipo BackgroundType.OwnBackground. Solo lectura [`IFillFormat`](../ifillformat). |
| [Presentation](../../aspose.slides/background/presentation) { get; } | Devuelve la presentación padre de una diapositiva. Solo lectura [`IPresentation`](../ipresentation). |
| [Slide](../../aspose.slides/background/slide) { get; } | Devuelve la diapositiva padre de una forma. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [StyleColor](../../aspose.slides/background/stylecolor) { get; } | Devuelve un ColorFormat para un relleno de tipo BackgroundType.Themed. Solo lectura [`IColorFormat`](../icolorformat). |
| [StyleIndex](../../aspose.slides/background/styleindex) { get; set; } | Devuelve un índice de relleno de tipo BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura UInt16. |
| [Type](../../aspose.slides/background/type) { get; set; } | Devuelve un tipo de relleno de fondo. Lectura/escritura [`BackgroundType`](../backgroundtype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/background/geteffective)() | Obtiene los datos efectivos del fondo con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Véase también

* clase [PVIObject](../pviobject)
* interfaz [IBackground](../ibackground)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->