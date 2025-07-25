---
title: IEffect
second_title: Aspose.Slides para .NET Referencia de API
description: Representa el efecto de animación.
type: docs
weight: 410
url: /es/aspose.slides.animation/ieffect/
---

## Interfaz IEffect

Representa el efecto de animación.

```csharp
public interface IEffect
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AfterAnimationColor](../../aspose.slides.animation/ieffect/afteranimationcolor) { get; set; } | Define un color después de la animación para el efecto. Lectura/escritura [`IColorFormat`](../../aspose.slides/icolorformat). |
| [AfterAnimationType](../../aspose.slides.animation/ieffect/afteranimationtype) { get; set; } | Define un tipo después de la animación para el efecto. Lectura/escritura [`AfterAnimationType`](./afteranimationtype). |
| [AnimateTextType](../../aspose.slides.animation/ieffect/animatetexttype) { get; set; } | Define un tipo de animación de texto para el efecto. El texto de la forma se puede animar por letra, por palabra o todo a la vez. Lectura/escritura [`AnimateTextType`](./animatetexttype). |
| [Behaviors](../../aspose.slides.animation/ieffect/behaviors) { get; set; } | Devuelve la colección de comportamientos para el efecto. Lectura/escritura [`IBehaviorCollection`](../ibehaviorcollection). |
| [DelayBetweenTextParts](../../aspose.slides.animation/ieffect/delaybetweentextparts) { get; set; } | Define un retraso entre las partes del texto animado (palabras o letras). Un valor positivo especifica el porcentaje de duración del efecto. Un valor negativo especifica el retraso en segundos. Lectura/escritura Single. |
| [PresetClassType](../../aspose.slides.animation/ieffect/presetclasstype) { get; set; } | Define la clase del efecto. Lectura/escritura [`EffectPresetClassType`](../effectpresetclasstype). |
| [Sequence](../../aspose.slides.animation/ieffect/sequence) { get; } | Devuelve una secuencia para un efecto. Solo lectura [`ISequence`](../isequence). |
| [Sound](../../aspose.slides.animation/ieffect/sound) { get; set; } | Define un sonido incrustado para el efecto. Lectura/escritura [`IAudio`](../../aspose.slides/iaudio). |
| [StopPreviousSound](../../aspose.slides.animation/ieffect/stopprevioussound) { get; set; } | Este atributo especifica si el efecto de animación detiene el sonido anterior. Lectura/escritura Boolean. |
| [Subtype](../../aspose.slides.animation/ieffect/subtype) { get; set; } | Define el subtipo del efecto. Lectura/escritura [`EffectSubtype`](../effectsubtype). |
| [TargetShape](../../aspose.slides.animation/ieffect/targetshape) { get; } | Devuelve la forma objetivo para el efecto. Solo lectura [`IShape`](../../aspose.slides/ishape). |
| [TextAnimation](../../aspose.slides.animation/ieffect/textanimation) { get; } | Devuelve la animación de texto. Solo lectura [`ITextAnimation`](../itextanimation). |
| [Timing](../../aspose.slides.animation/ieffect/timing) { get; set; } | Define el valor de temporización para el efecto. Lectura/escritura [`ITiming`](../itiming). |
| [Type](../../aspose.slides.animation/ieffect/type) { get; set; } | Define el tipo de efecto. Lectura/escritura [`EffectType`](../effecttype). |

### Véase también

* namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->