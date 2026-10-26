---
title: AddEffect
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Dodaj nowy efekt na koniec sekwencji.
type: docs
weight: 50
url: /pl/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Dodaj nowy efekt na koniec sekwencji.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | IShape | Obiekt Shape [`IShape`](../../../aspose.slides/ishape) do dodania efektu |
| effectType | EffectType | Typ efektu animacji [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy efektu animacji [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ wyzwalacza efektu [`EffectTriggerType`](../../effecttriggertype) |

### Wartość zwracana

Nowy obiekt efektu [`IEffect`](../../ieffect)

### Zobacz także

* interfejs [IEffect](../../ieffect)
* interfejs [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfejs [ISequence](../../isequence)
* przestrzeń nazw [Aspose.Slides.Animation](../../isequence)
* zasób [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Dodaj nowy efekt animacji dla akapitu na koniec sekwencji.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| paragraph | IParagraph | Obiekt Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Typ efektu animacji [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy efektu animacji [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ wyzwalacza efektu [`EffectTriggerType`](../../effecttriggertype) |

### Wartość zwracana

Nowy obiekt efektu [`IEffect`](../../ieffect)

### Przykłady

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // wybierz akapit, aby dodać efekt
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // dodaj efekt animacji Fly do wybranego akapitu
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Zobacz także

* interfejs [IEffect](../../ieffect)
* interfejs [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfejs [ISequence](../../isequence)
* przestrzeń nazw [Aspose.Slides.Animation](../../isequence)
* zasób [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | IChart | Obiekt Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Typ efektu animacji [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Indeks Int32 |
| effectType | EffectType | Typ efektu animacji [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy efektu animacji [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ wyzwalacza efektu [`EffectTriggerType`](../../effecttriggertype) |

### Wartość zwracana

Nowy obiekt efektu [`IEffect`](../../ieffect)

### Zobacz także

* interfejs [IEffect](../../ieffect)
* interfejs [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfejs [ISequence](../../isequence)
* przestrzeń nazw [Aspose.Slides.Animation](../../isequence)
* zasób [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | IChart | Obiekt Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Typ efektu animacji [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Indeks serii wykresu Int32 |
| categoriesIndex | Int32 | Indeks kategorii Int32 |
| effectType | EffectType | Typ efektu animacji [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Podtypy efektu animacji [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Typ wyzwalacza efektu [`EffectTriggerType`](../../effecttriggertype) |

### Wartość zwracana

Nowy obiekt efektu [`IEffect`](../../ieffect)

### Zobacz także

* interfejs [IEffect](../../ieffect)
* interfejs [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interfejs [ISequence](../../isequence)
* przestrzeń nazw [Aspose.Slides.Animation](../../isequence)
* zasób [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->