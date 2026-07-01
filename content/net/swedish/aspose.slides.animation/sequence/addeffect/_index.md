---
title: AddEffect
second_title: Aspose.Sildes för .NET API-referens
description: Lägg till en ny effekt i slutet av sekvensen.
type: docs
weight: 40
url: /sv/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Lägg till en ny effekt i slutet av sekvensen.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shape | IShape | Shape-objekt [`IShape`](../../../aspose.slides/ishape) för att lägga till en effekt |
| effectType | EffectType | Typ av en animeringseffekt [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Underkategorier av animeringseffekt [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Utlösningstyp för effekt [`EffectTriggerType`](../../effecttriggertype) |

### Returvärde

Nytt effektobjekt [`IEffect`](../../ieffect)

### Se även

* gränssnitt [IEffect](../../ieffect)
* gränssnitt [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klass [Sequence](../../sequence)
* namnrymd [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Lägg till en ny animeringseffekt för stycket i slutet av sekvensen.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph-objekt [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Typ av en animeringseffekt [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Underkategorier av animeringseffekt [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Utlösningstyp för effekt [`EffectTriggerType`](../../effecttriggertype) |

### Returvärde

Nytt effektobjekt [`IEffect`](../../ieffect)

### Exempel

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // välj stycke för att lägga till effekt
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // lägg till Fly-animeringseffekt på valt stycke
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Se även

* gränssnitt [IEffect](../../ieffect)
* gränssnitt [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klass [Sequence](../../sequence)
* namnrymd [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Lägger till den nya diagramanimeringseffekten för kategori eller serie i slutet av sekvensen.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Chart-objekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Typ av en animeringseffekt [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Typ av en animeringseffekt [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Underkategorier av animeringseffekt [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Utlösningstyp för effekt [`EffectTriggerType`](../../effecttriggertype) |

### Returvärde

Nytt effektobjekt [`IEffect`](../../ieffect)

### Se även

* gränssnitt [IEffect](../../ieffect)
* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klass [Sequence](../../sequence)
* namnrymd [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Lägger till den nya diagramanimeringseffekten för element i kategori eller serie i slutet av sekvensen.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Chart-objekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Typ av en animeringseffekt [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index för diagramserie Int32 |
| categoriesIndex | Int32 | Index för kategori Int32 |
| effectType | EffectType | Typ av en animeringseffekt [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Underkategorier av animeringseffekt [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Utlösningstyp för effekt [`EffectTriggerType`](../../effecttriggertype) |

### Returvärde

Nytt effektobjekt [`IEffect`](../../ieffect)

### Se även

* gränssnitt [IEffect](../../ieffect)
* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klass [Sequence](../../sequence)
* namnrymd [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->