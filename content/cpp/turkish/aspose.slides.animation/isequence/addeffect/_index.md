---
title: AddEffect()
second_title: C++ için Aspose.Slides API Referansı
description: Yeni efekti sekansın sonuna ekler.
type: docs
weight: 144
url: /tr/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metodu

Yeni efekti sekansın sonuna ekler.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) nesnesi [IShape](../../../aspose.slides/ishape/) bir etki eklemek için |
| effectType | [EffectType](../../effecttype/) | Animasyon etkisi türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon etkisi alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Etkinin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Yeni etki nesnesi [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metodu

Paragraf için yeni animasyon etkisini sekansın sonuna ekler.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) nesnesi [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Animasyon etkisi türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon etkisi alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Etkinin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Yeni etki nesnesi [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metodu

Kategori veya seri için yeni grafik animasyon etkisini sekansın sonuna ekler.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafik nesnesi [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Animasyon etkisi türü [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Animasyon etkisi türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon etkisi alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Etkinin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Yeni etki nesnesi [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metodu

Kategori veya serideki öğeler için yeni grafik animasyon etkisini sekansın sonuna ekler.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafik nesnesi [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Animasyon etkisi türü [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Grafik serisi indeksi **int32_t** |
| categoriesIndex | **int32_t** | Kategori indeksi **int32_t** |
| effectType | [EffectType](../../effecttype/) | Animasyon etkisi türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon etkisi alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Etkinin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Yeni etki nesnesi [IEffect](../../ieffect/)

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// select paragraph to add effect
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// add Fly animation effect to selected paragraph
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## İlgili

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [ISequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)