---
title: AddEffect()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni efekti sıranın sonuna ekler.
type: docs
weight: 157
url: /tr/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metod

Yeni efekti sıranın sonuna ekler.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) nesnesi [IShape](../../../aspose.slides/ishape/) bir efekt eklemek için |
| effectType | [EffectType](../../effecttype/) | Bir animasyon efekti [EffectType](../../effecttype/) türü |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon efekti [EffectSubtype](../../effectsubtype/) alt türleri |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Efektin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni efekt nesnesi [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metod

Paragraf için yeni animasyon efektini sıranın sonuna ekler.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) nesnesi [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Bir animasyon efekti [EffectType](../../effecttype/) türü |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon efekti [EffectSubtype](../../effectsubtype/) alt türleri |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Efektin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni efekt nesnesi [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod

Kategori veya seri için yeni grafik animasyon efektini sıranın sonuna ekler.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafik nesnesi [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Bir animasyon efekti [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) türü |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Bir animasyon efekti [EffectType](../../effecttype/) türü |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon efekti [EffectSubtype](../../effectsubtype/) alt türleri |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Efektin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni efekt nesnesi [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod

Kategori veya serideki öğeler için yeni grafik animasyon efektini sıranın sonuna ekler.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafik nesnesi [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Bir animasyon efekti [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) türü |
| seriesIndex | **int32_t** | Index of chart series **int32_t** |
| categoriesIndex | **int32_t** | Index of category **int32_t** |
| effectType | [EffectType](../../effecttype/) | Bir animasyon efekti [EffectType](../../effecttype/) türü |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon efekti [EffectSubtype](../../effectsubtype/) alt türleri |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Efektin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni efekt nesnesi [IEffect](../../ieffect/)

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// select paragraph to add effect
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// add Fly animation effect to selected paragraph
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Ayrıca Bakınız

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [Sequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)