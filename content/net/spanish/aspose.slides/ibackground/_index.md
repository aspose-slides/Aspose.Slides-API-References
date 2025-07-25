---
title: IBackground
second_title: Aspose.Sildes para .NET Referencia de API
description: Representa el fondo de una diapositiva.
type: docs
weight: 5070
url: /es/aspose.slides/ibackground/
---

## Interfaz IBackground

Representa el fondo de una diapositiva.

```csharp
public interface IBackground : IFillParamSource, ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ibackground/asifillparamsource) { get; } | Devuelve la interfaz IFillParamSource. Solo lectura [`IFillParamSource`](../ifillparamsource). |
| [AsISlideComponent](../../aspose.slides/ibackground/asislidecomponent) { get; } | Devuelve la interfaz ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [EffectFormat](../../aspose.slides/ibackground/effectformat) { get; } | Devuelve un EffectFormat para el relleno BackgroundType.OwnBackground. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ibackground/fillformat) { get; } | Devuelve un FillFormat para el relleno BackgroundType.OwnBackground. Solo lectura [`IFillFormat`](../ifillformat). |
| [StyleColor](../../aspose.slides/ibackground/stylecolor) { get; } | Devuelve un ColorFormat para un relleno BackgroundType.Themed. Solo lectura [`IColorFormat`](../icolorformat). |
| [StyleIndex](../../aspose.slides/ibackground/styleindex) { get; set; } | Devuelve un índice de relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura UInt16. |
| [Type](../../aspose.slides/ibackground/type) { get; set; } | Devuelve un tipo de relleno de fondo. Lectura/escritura [`BackgroundType`](../backgroundtype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetEffective](../../aspose.slides/ibackground/geteffective)() | Obtiene los datos de fondo efectivos con la herencia aplicada. |

### Véase También

* interfaz [IFillParamSource](../ifillparamsource)
* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->