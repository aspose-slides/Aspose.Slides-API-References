---
title: ISequence
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa colección de secuencias de efectos.
type: docs
weight: 510
url: /es/aspose.slides.animation/isequence/
---

## Interfaz ISequence

Representa secuencia (colección de efectos).

```csharp
public interface ISequence : IEnumerable<IEffect>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.animation/isequence/asienumerable) { get; } | Permite obtener la interfaz base IEnumerable. Solo lectura IEnumerable. |
| [Count](../../aspose.slides.animation/isequence/count) { get; } | Devuelve el número de efectos en una secuencia. Solo lectura Int32. |
| [Item](../../aspose.slides.animation/isequence/item) { get; } | Devuelve un efecto en el índice especificado. |
| [TriggerShape](../../aspose.slides.animation/isequence/triggershape) { get; set; } | Devuelve o establece la forma objetivo para la secuencia INTERACTIVA. Si la secuencia no es interactiva, entonces devuelve null. Lectura/escritura [`IShape`](../../aspose.slides/ishape). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_2)(IParagraph, EffectType, EffectSubtype, EffectTriggerType) | Agrega un nuevo efecto de animación para el párrafo al final de la secuencia. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_3)(IShape, EffectType, EffectSubtype, EffectTriggerType) | Agrega un nuevo efecto al final de la secuencia. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect)(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) | Agrega el nuevo efecto de animación del gráfico para categoría o serie al final de la secuencia. |
| [AddEffect](../../aspose.slides.animation/isequence/addeffect#addeffect_1)(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) | Agrega el nuevo efecto de animación del gráfico para elementos en categoría o serie al final de la secuencia. |
| [Clear](../../aspose.slides.animation/isequence/clear)() | Elimina todos los efectos de una colección. |
| [GetCount](../../aspose.slides.animation/isequence/getcount)(IShape) | Devuelve la cantidad de efectos para la forma especificada. |
| [GetEffectsByParagraph](../../aspose.slides.animation/isequence/geteffectsbyparagraph)(IParagraph) | Devuelve un array de efectos para el párrafo especificado. |
| [GetEffectsByShape](../../aspose.slides.animation/isequence/geteffectsbyshape)(IShape) | Devuelve un array de efectos para la forma especificada. |
| [Remove](../../aspose.slides.animation/isequence/remove)(IEffect) | Elimina el efecto especificado de una colección. |
| [RemoveAt](../../aspose.slides.animation/isequence/removeat)(int) | Elimina un efecto de una colección. |
| [RemoveByShape](../../aspose.slides.animation/isequence/removebyshape)(IShape) | Elimina el efecto para la forma especificada. |

### Véase también

* interfaz [IEffect](../ieffect)
* espacio de nombres [Aspose.Slides.Animation](../../aspose.slides.animation)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->