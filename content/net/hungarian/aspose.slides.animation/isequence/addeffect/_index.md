---
title: AddEffect
second_title: Aspose.Sildes .NET API-referencia
description: Új effektust ad a szekvencia végéhez.
type: docs
weight: 50
url: /hu/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Új effektust ad a szekvencia végéhez.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | IShape | Shape objektum [`IShape`](../../../aspose.slides/ishape) egy effektus hozzáadásához |
| effectType | EffectType | Animációs effektus típusa [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interfész [IEffect](../../ieffect)
* interfész [IShape](../../../aspose.slides/ishape)
* enumeráció [EffectType](../../effecttype)
* enumeráció [EffectSubtype](../../effectsubtype)
* enumeráció [EffectTriggerType](../../effecttriggertype)
* interfész [ISequence](../../isequence)
* névtér [Aspose.Slides.Animation](../../isequence)
* összeállítás [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Új animációs effektust ad a bekezdéshez a szekvencia végén.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph objektum [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Animációs effektus típusa [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Példák

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // válassza ki a bekezdést az effektus hozzáadásához
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // adja hozzá a Fly animációs effektust a kiválasztott bekezdéshez
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Lásd még

* interfész [IEffect](../../ieffect)
* interfész [IParagraph](../../../aspose.slides/iparagraph)
* enumeráció [EffectType](../../effecttype)
* enumeráció [EffectSubtype](../../effectsubtype)
* enumeráció [EffectTriggerType](../../effecttriggertype)
* interfész [ISequence](../../isequence)
* névtér [Aspose.Slides.Animation](../../isequence)
* összeállítás [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Új chart animációs effektust ad a kategória vagy sorozat számára a szekvencia végén.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | IChart | Chart objektum [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Animációs effektus típusa [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 index |
| effectType | EffectType | Animációs effektus típusa [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interfész [IEffect](../../ieffect)
* interfész [IChart](../../../aspose.slides.charts/ichart)
* enumeráció [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enumeráció [EffectType](../../effecttype)
* enumeráció [EffectSubtype](../../effectsubtype)
* enumeráció [EffectTriggerType](../../effecttriggertype)
* interfész [ISequence](../../isequence)
* névtér [Aspose.Slides.Animation](../../isequence)
* összeállítás [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Új chart animációs effektust ad a kategória vagy sorozat elemei számára a szekvencia végén.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | IChart | Chart objektum [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Animációs effektus típusa [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Int32 a diagram sorozat indexe |
| categoriesIndex | Int32 | Int32 a kategória indexe |
| effectType | EffectType | Animációs effektus típusa [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interfész [IEffect](../../ieffect)
* interfész [IChart](../../../aspose.slides.charts/ichart)
* enumeráció [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enumeráció [EffectType](../../effecttype)
* enumeráció [EffectSubtype](../../effectsubtype)
* enumeráció [EffectTriggerType](../../effecttriggertype)
* interfész [ISequence](../../isequence)
* névtér [Aspose.Slides.Animation](../../isequence)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->