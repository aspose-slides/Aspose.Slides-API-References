---
title: AddEffect
second_title: Aspose.Sildes pro .NET – referenční dokumentace API
description: Přidá nový efekt na konec sekvence.
type: docs
weight: 50
url: /cs/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Přidá nový efekt na konec sekvence.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | IShape | Objekt Shape [`IShape`](../../../aspose.slides/ishape) pro přidání efektu |
| effectType | EffectType | Typ animačního efektu [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy animačního efektu [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ spouštění efektu [`EffectTriggerType`](../../effecttriggertype) |

### Návratová hodnota

Nový objekt Effect [`IEffect`](../../ieffect)

### Viz také

* rozhraní [IEffect](../../ieffect)
* rozhraní [IShape](../../../aspose.slides/ishape)
* výčet [EffectType](../../effecttype)
* výčet [EffectSubtype](../../effectsubtype)
* výčet [EffectTriggerType](../../effecttriggertype)
* rozhraní [ISequence](../../isequence)
* jmenný prostor [Aspose.Slides.Animation](../../isequence)
* sestava [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Přidá nový animační efekt pro odstavce na konec sekvence.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| paragraph | IParagraph | Objekt Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Typ animačního efektu [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy animačního efektu [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ spouštění efektu [`EffectTriggerType`](../../effecttriggertype) |

### Návratová hodnota

Nový objekt Effect [`IEffect`](../../ieffect)

### Příklady

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // vyberte odstavec pro přidání efektu
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // přidejte efekt Fly animace do vybraného odstavce
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Viz také

* rozhraní [IEffect](../../ieffect)
* rozhraní [IParagraph](../../../aspose.slides/iparagraph)
* výčet [EffectType](../../effecttype)
* výčet [EffectSubtype](../../effectsubtype)
* výčet [EffectTriggerType](../../effecttriggertype)
* rozhraní [ISequence](../../isequence)
* jmenný prostor [Aspose.Slides.Animation](../../isequence)
* sestava [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Přidá nový animační efekt grafu pro kategorii nebo řadu na konec sekvence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | IChart | Objekt Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Typ animačního efektu [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Typ animačního efektu [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy animačního efektu [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ spouštění efektu [`EffectTriggerType`](../../effecttriggertype) |

### Návratová hodnota

Nový objekt Effect [`IEffect`](../../ieffect)

### Viz také

* rozhraní [IEffect](../../ieffect)
* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* výčet [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* výčet [EffectType](../../effecttype)
* výčet [EffectSubtype](../../effectsubtype)
* výčet [EffectTriggerType](../../effecttriggertype)
* rozhraní [ISequence](../../isequence)
* jmenný prostor [Aspose.Slides.Animation](../../isequence)
* sestava [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Přidá nový animační efekt grafu pro prvky v kategorii nebo řadě na konec sekvence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| chart | IChart | Objekt Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Typ animačního efektu [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index řady grafu Int32 |
| categoriesIndex | Int32 | Index kategorie Int32 |
| effectType | EffectType | Typ animačního efektu [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy animačního efektu [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ spouštění efektu [`EffectTriggerType`](../../effecttriggertype) |

### Návratová hodnota

Nový objekt Effect [`IEffect`](../../ieffect)

### Viz také

* rozhraní [IEffect](../../ieffect)
* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* výčet [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* výčet [EffectType](../../effecttype)
* výčet [EffectSubtype](../../effectsubtype)
* výčet [EffectTriggerType](../../effecttriggertype)
* rozhraní [ISequence](../../isequence)
* jmenný prostor [Aspose.Slides.Animation](../../isequence)
* sestava [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->