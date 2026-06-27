---
title: AddEffect
second_title: Aspose.Sildes for .NET API Referansı
description: Diziye yeni efekti ekler.
type: docs
weight: 40
url: /tr/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Yeni efekti dizinin sonuna ekler.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | IShape | Shape nesnesi [`IShape`](../../../aspose.slides/ishape) bir efekt eklemek için |
| effectType | EffectType | Bir animasyon efektinin türü [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animasyon efektinin alt türleri [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Efektin tetikleme türü [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

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

Paragraf için yeni animasyon efekti dizinin sonuna ekler.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph nesnesi [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Bir animasyon efektinin türü [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animasyon efektinin alt türleri [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Efektin tetikleme türü [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Örnekler

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // efekti eklemek için paragrafı seç
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // seçili paragrafa Fly animasyon efekti ekle
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Ayrıca Bakınız

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

Kategori ya da seriye ait yeni grafik animasyon efektini dizinin sonuna ekler.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | IChart | Chart nesnesi [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Bir animasyon efektinin türü [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Dizin Int32 |
| effectType | EffectType | Bir animasyon efektinin türü [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animasyon efektinin alt türleri [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Efektin tetikleme türü [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

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

Kategori ya da serideki öğeler için yeni grafik animasyon efektini dizinin sonuna ekler.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | IChart | Chart nesnesi [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Bir animasyon efektinin türü [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Chart serisinin dizini Int32 |
| categoriesIndex | Int32 | Kategorinin dizini Int32 |
| effectType | EffectType | Bir animasyon efektinin türü [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Animasyon efektinin alt türleri [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Efektin tetikleme türü [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

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