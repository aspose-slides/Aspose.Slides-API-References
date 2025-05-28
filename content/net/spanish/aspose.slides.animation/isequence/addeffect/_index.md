---
title: AddEffect
second_title: Referencia de API de Aspose.Slides para .NET
description: Agregar un nuevo efecto al final de la secuencia.
type: docs
weight: 50
url: /es/aspose.slides.animation/isequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Agregar un nuevo efecto al final de la secuencia.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | IShape | Objeto de forma [`IShape`](../../../aspose.slides/ishape) para agregar un efecto |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de desencadenador del efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase también

* interfaz [IEffect](../../ieffect)
* interfaz [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaz [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Agregar un nuevo efecto de animación para el párrafo al final de la secuencia.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | IParagraph | Objeto de párrafo [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de desencadenador del efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Ejemplos

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // seleccionar párrafo para agregar efecto
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // agregar efecto de animación Fly al párrafo seleccionado
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Véase también

* interfaz [IEffect](../../ieffect)
* interfaz [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaz [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Agrega un nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | IChart | Objeto de gráfico [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Tipo de un efecto de animación [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Índice Int32 |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de desencadenador del efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase también

* interfaz [IEffect](../../ieffect)
* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaz [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Agrega un nuevo efecto de animación de gráfico para elementos en categoría o serie al final de la secuencia.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | IChart | Objeto de gráfico [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipo de un efecto de animación [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Índice de la serie de gráficos Int32 |
| categoriesIndex | Int32 | Índice de categoría Int32 |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de desencadenador del efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase también

* interfaz [IEffect](../../ieffect)
* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaz [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->