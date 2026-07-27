---
title: AddEffect()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um novo efeito ao final da sequência.
type: docs
weight: 157
url: /pt/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method

Adiciona um novo efeito ao final da sequência.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objeto [IShape](../../../aspose.slides/ishape/) para adicionar um efeito |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Novo objeto de efeito [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method

Adiciona um novo efeito de animação para o parágrafo ao final da sequência.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objeto [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Novo objeto de efeito [IEffect](../../ieffect/)

## Remarks

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

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objeto de gráfico [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Índice **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Novo objeto de efeito [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Adiciona o novo efeito de animação de gráfico para elementos na categoria ou série ao final da sequência.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objeto de gráfico [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Índice da série do gráfico **int32_t** |
| categoriesIndex | **int32_t** | Índice da categoria **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Novo objeto de efeito [IEffect](../../ieffect/)

## See Also

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