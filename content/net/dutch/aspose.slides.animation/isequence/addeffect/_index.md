---
title: AddEffect
second_title: Aspose.Sildes voor .NET API-referentie
description: Voegt een nieuw effect toe aan het einde van de reeks.
type: docs
weight: 50
url: /nl/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Voegt een nieuw effect toe aan het einde van de reeks.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) voor het toevoegen van een effect |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Retourwaarde

Nieuw effectobject [`IEffect`](../../ieffect)

### Zie ook

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* naamruimte [Aspose.Slides.Animation](../../isequence)
* assemblage [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Voegt een nieuw animatie-effect toe voor alinea aan het einde van de reeks.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Retourwaarde

Nieuw effectobject [`IEffect`](../../ieffect)

### Voorbeelden

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // selecteer alinea om effect toe te voegen
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // voeg Fly-animatie-effect toe aan geselecteerde alinea
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Zie ook

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* naamruimte [Aspose.Slides.Animation](../../isequence)
* assemblage [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Voegt het nieuwe diagramanimatie-effect toe voor categorie of serie aan het einde van de reeks.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type van een animatie-effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Retourwaarde

Nieuw effectobject [`IEffect`](../../ieffect)

### Zie ook

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* naamruimte [Aspose.Slides.Animation](../../isequence)
* assemblage [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Voegt het nieuwe diagramanimatie-effect toe voor elementen in een categorie of serie aan het einde van de reeks.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type van een animatie-effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index van chart-series Int32 |
| categoriesIndex | Int32 | Index van categorie Int32 |
| effectType | EffectType | Type van een animatie-effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes van animatie-effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Triggertype van effect [`EffectTriggerType`](../../effecttriggertype) |

### Retourwaarde

Nieuw effectobject [`IEffect`](../../ieffect)

### Zie ook

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* naamruimte [Aspose.Slides.Animation](../../isequence)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->