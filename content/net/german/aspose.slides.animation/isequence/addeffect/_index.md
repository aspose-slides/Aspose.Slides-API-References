---
title: AddEffect
second_title: Aspose.Slides für .NET API Referenz
description: Fügen Sie einen neuen Effekt am Ende der Sequenz hinzu.
type: docs
weight: 50
url: /de/aspose.slides.animation/isequence/addeffect/
---

## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Fügen Sie einen neuen Effekt am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | IShape | Shape-Objekt [`IShape`](../../../aspose.slides/ishape) zum Hinzufügen eines Effekts |
| effectType | EffectType | Art eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen des Animationseffekts [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösertyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* Schnittstelle [IEffect](../../ieffect)
* Schnittstelle [IShape](../../../aspose.slides/ishape)
* Enum [EffectType](../../effecttype)
* Enum [EffectSubtype](../../effectsubtype)
* Enum [EffectTriggerType](../../effecttriggertype)
* Schnittstelle [ISequence](../../isequence)
* Namespace [Aspose.Slides.Animation](../../isequence)
* Assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Fügen Sie einen neuen Animationseffekt für den Absatz am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | IParagraph | Absatzobjekt [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Art eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen des Animationseffekts [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösertyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Beispiele

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // Wählen Sie den Absatz aus, um den Effekt hinzuzufügen
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // Fügen Sie den Fly-Animationseffekt zum ausgewählten Absatz hinzu
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Siehe auch

* Schnittstelle [IEffect](../../ieffect)
* Schnittstelle [IParagraph](../../../aspose.slides/iparagraph)
* Enum [EffectType](../../effecttype)
* Enum [EffectSubtype](../../effectsubtype)
* Enum [EffectTriggerType](../../effecttriggertype)
* Schnittstelle [ISequence](../../isequence)
* Namespace [Aspose.Slides.Animation](../../isequence)
* Assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Fügt den neuen Chart-Animationseffekt für Kategorie oder Serie am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | IChart | Chart-Objekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Art eines Animationseffekts [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Art eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen des Animationseffekts [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösertyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* Schnittstelle [IEffect](../../ieffect)
* Schnittstelle [IChart](../../../aspose.slides.charts/ichart)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* Enum [EffectType](../../effecttype)
* Enum [EffectSubtype](../../effectsubtype)
* Enum [EffectTriggerType](../../effecttriggertype)
* Schnittstelle [ISequence](../../isequence)
* Namespace [Aspose.Slides.Animation](../../isequence)
* Assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Fügt den neuen Chart-Animationseffekt für Elemente in Kategorie oder Serie am Ende der Sequenz hinzu.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chart | IChart | Chart-Objekt [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Art eines Animationseffekts [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index der Chart-Serie Int32 |
| categoriesIndex | Int32 | Index der Kategorie Int32 |
| effectType | EffectType | Art eines Animationseffekts [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypen des Animationseffekts [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Auslösertyp des Effekts [`EffectTriggerType`](../../effecttriggertype) |

### Rückgabewert

Neues Effektobjekt [`IEffect`](../../ieffect)

### Siehe auch

* Schnittstelle [IEffect](../../ieffect)
* Schnittstelle [IChart](../../../aspose.slides.charts/ichart)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* Enum [EffectType](../../effecttype)
* Enum [EffectSubtype](../../effectsubtype)
* Enum [EffectTriggerType](../../effecttriggertype)
* Schnittstelle [ISequence](../../isequence)
* Namespace [Aspose.Slides.Animation](../../isequence)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->