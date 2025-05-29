---
title: AddEffect
second_title: Referencia de la API de Aspose.Slides para .NET
description: Añadir un nuevo efecto al final de la secuencia.
type: docs
weight: 40
url: /es/aspose.slides.animation/sequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Añadir un nuevo efecto al final de la secuencia.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | IShape | Objeto de forma [`IShape`](../../../aspose.slides/ishape) para añadir un efecto |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de activador de efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase También

* interfaz [IEffect](../../ieffect)
* interfaz [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* clase [Sequence](../../sequence)
* espacio de nombres [Aspose.Slides.Animation](../../sequence)
* ensamblaje [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Añadir un nuevo efecto de animación para párrafo al final de la secuencia.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | IParagraph | Objeto de párrafo [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de activador de efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Ejemplos

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // seleccionar párrafo para añadir efecto
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // añadir efecto de animación de vuelo al párrafo seleccionado
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Véase También

* interfaz [IEffect](../../ieffect)
* interfaz [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* clase [Sequence](../../sequence)
* espacio de nombres [Aspose.Slides.Animation](../../sequence)
* ensamblaje [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Añade el nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia.

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
| triggerType | EffectTriggerType | Tipo de activador de efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase También

* interfaz [IEffect](../../ieffect)
* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* clase [Sequence](../../sequence)
* espacio de nombres [Aspose.Slides.Animation](../../sequence)
* ensamblaje [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Añade el nuevo efecto de animación de gráfico para elementos en categoría o serie al final de la secuencia.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | IChart | Objeto de gráfico [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipo de un efecto de animación [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Índice de serie de gráfico Int32 |
| categoriesIndex | Int32 | Índice de categoría Int32 |
| effectType | EffectType | Tipo de un efecto de animación [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo de activador de efecto [`EffectTriggerType`](../../effecttriggertype) |

### Valor de Retorno

Nuevo objeto de efecto [`IEffect`](../../ieffect)

### Véase También

* interfaz [IEffect](../../ieffect)
* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* clase [Sequence](../../sequence)
* espacio de nombres [Aspose.Slides.Animation](../../sequence)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->