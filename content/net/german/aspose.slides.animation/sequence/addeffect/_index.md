---
title: AddEffect
second_title: Aspose.Slides für .NET API Referenz
description: Fügen Sie einen neuen Effekt am Ende der Sequenz hinzu.
type: docs
weight: 40
url: /de/aspose.slides.animation/sequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Fügen Sie einen neuen Effekt am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | IShape | Shape-Objekt [`IShape`](../../../aspose.slides/ishape) zum Hinzufügen eines Effekts |
| effectType | EffectType | Typ eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen von Animationseffekten [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösetyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Fügen Sie einen neuen Animationseffekt für einen Absatz am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | IParagraph | Absatzobjekt [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Typ eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen von Animationseffekten [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösetyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Beispiele

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // Absatz auswählen, um einen Effekt hinzuzufügen
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // Fly-Animationseffekt zum gewählten Absatz hinzufügen
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Siehe auch

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Fügt den neuen Diagrammanimationseffekt für Kategorie oder Serie am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | IChart | Diagrammobjekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Typ eines Animationseffekts [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Typ eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen von Animationseffekten [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösetyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Fügt den neuen Diagrammanimationseffekt für Elemente in Kategorie oder Serie am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | IChart | Diagrammobjekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Typ eines Animationseffekts [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index der Diagrammserie Int32 |
| categoriesIndex | Int32 | Index der Kategorie Int32 |
| effectType | EffectType | Typ eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen von Animationseffekten [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösetyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->