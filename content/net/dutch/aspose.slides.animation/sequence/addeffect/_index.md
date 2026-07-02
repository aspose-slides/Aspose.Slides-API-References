---
title: AddEffect
second_title: Aspose.Sildes voor .NET API-referentie
description: Voeg een nieuw effect toe aan het einde van de reeks.
type: docs
weight: 40
url: /nl/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Voeg een nieuw effect toe aan het einde van de reeks.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | IShape | Shape-object [`IShape`](../../../aspose.slides/ishape) voor het toevoegen van een effect |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtype van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Nieuw effectobject [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klasse [Sequence](../../sequence)
* naamruimte [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Voeg een nieuw animatie-effect toe voor alinea aan het einde van de reeks.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph-object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtype van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Nieuw effectobject [`IEffect`](../../ieffect)

### Examples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // selecteer de alinea om een effect toe te voegen
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // voeg Fly-animatie-effect toe aan de geselecteerde alinea
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### See Also

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klasse [Sequence](../../sequence)
* naamruimte [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Voegt het nieuwe diagram-animatie-effect toe voor categorie of serie aan het einde van de reeks.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | IChart | Chart-object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type van een animatie-effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtype van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Nieuw effectobject [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klasse [Sequence](../../sequence)
* naamruimte [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Voegt het nieuwe diagram-animatie-effect toe voor elementen in categorie of serie aan het einde van de reeks.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | IChart | Chart-object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type van een animatie-effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index van diagramreeks Int32 |
| categoriesIndex | Int32 | Index van categorie Int32 |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtype van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

Nieuw effectobject [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* klasse [Sequence](../../sequence)
* naamruimte [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->