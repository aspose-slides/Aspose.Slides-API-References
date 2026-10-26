---
title: AddEffect
second_title: Aspose.Sildes için .NET API Referansı
description: Yeni efekti dizinin sonuna ekler.
type: docs
weight: 50
url: /tr/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Yeni efekti dizi sonuna ekler.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

* arayüz [IEffect](../../ieffect)
* arayüz [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* arayüz [ISequence](../../isequence)
* isim alanı [Aspose.Slides.Animation](../../isequence)
* derleme [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Paragraf için yeni animasyon efektini dizi sonuna ekler.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Örnekler

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // etki eklemek için paragrafı seç
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // seçilen paragraf için Fly animasyon efektini ekle
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### Ayrıca Bakınız

* arayüz [IEffect](../../ieffect)
* arayüz [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* arayüz [ISequence](../../isequence)
* isim alanı [Aspose.Slides.Animation](../../isequence)
* derleme [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Kategori veya seri için yeni grafik animasyon efektini dizi sonuna ekler.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

* arayüz [IEffect](../../ieffect)
* arayüz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* arayüz [ISequence](../../isequence)
* isim alanı [Aspose.Slides.Animation](../../isequence)
* derleme [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Kategori veya serideki öğeler için yeni grafik animasyon efektini dizi sonuna ekler.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index of chart series Int32 |
| categoriesIndex | Int32 | Index of category Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](../../ieffect)

### Ayrıca Bakınız

* arayüz [IEffect](../../ieffect)
* arayüz [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* arayüz [ISequence](../../isequence)
* isim alanı [Aspose.Slides.Animation](../../isequence)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->