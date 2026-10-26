---
title: AddEffect
second_title: Aspose.Sildes .NET API referencia
description: Új effektust ad a sorozat végéhez.
type: docs
weight: 40
url: /hu/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Új effektust ad a sorozat végéhez.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | IShape | Shape objektum [`IShape`](../../../aspose.slides/ishape) az effektus hozzáadásához |
| effectType | EffectType | Az animációs effektustípus [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Az animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Új animációs effektust ad a bekezdéshez a sorozat végéhez.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph objektum [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Az animációs effektustípus [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Az animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
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

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Új diagramanimációs effektust ad a kategória vagy sorozat számára a sorozat végéhez.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | IChart | Chart objektum [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Az animációs effektustípus [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Int32 index |
| effectType | EffectType | Az animációs effektustípus [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Az animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Új diagramanimációs effektust ad az elemeknek a kategóriában vagy sorozatban a sorozat végéhez.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chart | IChart | Chart objektum [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Az animációs effektustípus [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Chart sorozat Int32 index |
| categoriesIndex | Int32 | Kategória Int32 index |
| effectType | EffectType | Az animációs effektustípus [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Az animációs effektus altípusai [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Az effektus aktiválási típusa [`EffectTriggerType`](../../effecttriggertype) |

### Visszatérési érték

Új effektus objektum [`IEffect`](../../ieffect)

### Lásd még

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->