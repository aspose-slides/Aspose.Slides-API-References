---
title: AddEffect
second_title: Referencia de la API de Aspose.Slides para .NET
description: Añadir nuevo efecto al final de la secuencia.
type: docs
weight: 50
url: /es/net/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Añadir nuevo efecto al final de la secuencia.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| shape | IShape | Objeto de forma[`IShape`](../../../aspose.slides/ishape) para agregar un efecto |
| effectType | EffectType | Tipo de un efecto de animación[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Activar tipo de efecto[`EffectTriggerType`](../../effecttriggertype) |

### Valor_devuelto

Nuevo objeto de efecto[`IEffect`](../../ieffect)

### Ver también

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* espacio de nombres [Aspose.Slides.Animation](../../isequence)
* asamblea [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Agrega un nuevo efecto de animación para el párrafo al final de la secuencia.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| paragraph | IParagraph | Objeto de párrafo[`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipo de un efecto de animación[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Activar tipo de efecto[`EffectTriggerType`](../../effecttriggertype) |

### Valor_devuelto

Nuevo objeto de efecto[`IEffect`](../../ieffect)

### Ejemplos

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // selecciona el párrafo para agregar efecto
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // agrega el efecto de animación Fly al párrafo seleccionado
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Ver también

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* espacio de nombres [Aspose.Slides.Animation](../../isequence)
* asamblea [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Agrega el nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| chart | IChart | Objeto gráfico[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Tipo de un efecto de animación[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | ÍndiceInt32 |
| effectType | EffectType | Tipo de un efecto de animación[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Activar tipo de efecto[`EffectTriggerType`](../../effecttriggertype) |

### Valor_devuelto

Nuevo objeto de efecto[`IEffect`](../../ieffect)

### Ver también

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* espacio de nombres [Aspose.Slides.Animation](../../isequence)
* asamblea [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Agrega el nuevo efecto de animación de gráficos para elementos en categoría o serie al final de la secuencia.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| chart | IChart | Objeto gráfico[`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipo de un efecto de animación[`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Índice de series de gráficosInt32 |
| categoriesIndex | Int32 | Índice de categoríaInt32 |
| effectType | EffectType | Tipo de un efecto de animación[`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtipos de efecto de animación[`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Activar tipo de efecto[`EffectTriggerType`](../../effecttriggertype) |

### Valor_devuelto

Nuevo objeto de efecto[`IEffect`](../../ieffect)

### Ver también

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* espacio de nombres [Aspose.Slides.Animation](../../isequence)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
