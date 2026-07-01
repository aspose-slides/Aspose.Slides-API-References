---
title: AddEffect
second_title: Riferimento API Aspose.Sildes per .NET
description: Aggiunge un nuovo effetto alla fine della sequenza.
type: docs
weight: 50
url: /it/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Aggiunge un nuovo effetto alla fine della sequenza.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shape | IShape | Oggetto Shape [`IShape`](../../../aspose.slides/ishape) per l'aggiunta di un effetto |
| effectType | EffectType | Tipo di un effetto di animazione [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sottotipi di effetto di animazione [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo di attivazione dell'effetto [`EffectTriggerType`](../../effecttriggertype) |

### Valore restituito

Nuovo oggetto effect [`IEffect`](../../ieffect)

### Vedi anche

* interfaccia [IEffect](../../ieffect)
* interfaccia [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaccia [ISequence](../../isequence)
* spazio dei nomi [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | IParagraph | Oggetto Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Tipo di un effetto di animazione [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sottotipi di effetto di animazione [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo di attivazione dell'effetto [`EffectTriggerType`](../../effecttriggertype) |

### Valore restituito

Nuovo oggetto effect [`IEffect`](../../ieffect)

### Esempi

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // seleziona il paragrafo per aggiungere l'effetto
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // aggiungi l'effetto di animazione Fly al paragrafo selezionato
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Vedi anche

* interfaccia [IEffect](../../ieffect)
* interfaccia [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaccia [ISequence](../../isequence)
* spazio dei nomi [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Aggiunge il nuovo effetto di animazione del diagramma per la categoria o la serie alla fine della sequenza.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Oggetto Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Tipo di un effetto di animazione [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Indice Int32 |
| effectType | EffectType | Tipo di un effetto di animazione [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sottotipi di effetto di animazione [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo di attivazione dell'effetto [`EffectTriggerType`](../../effecttriggertype) |

### Valore restituito

Nuovo oggetto effect [`IEffect`](../../ieffect)

### Vedi anche

* interfaccia [IEffect](../../ieffect)
* interfaccia [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaccia [ISequence](../../isequence)
* spazio dei nomi [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Aggiunge il nuovo effetto di animazione del diagramma per gli elementi nella categoria o nella serie alla fine della sequenza.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Oggetto Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Tipo di un effetto di animazione [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Indice della serie del diagramma Int32 |
| categoriesIndex | Int32 | Indice della categoria Int32 |
| effectType | EffectType | Tipo di un effetto di animazione [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Sottotipi di effetto di animazione [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Tipo di attivazione dell'effetto [`EffectTriggerType`](../../effecttriggertype) |

### Valore restituito

Nuovo oggetto effect [`IEffect`](../../ieffect)

### Vedi anche

* interfaccia [IEffect](../../ieffect)
* interfaccia [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfaccia [ISequence](../../isequence)
* spazio dei nomi [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->