---
title: AddEffect()
second_title: Aspose.Slides para C++ Referência da API
description: Adiciona novo efeito ao final da sequência.
type: docs
weight: 144
url: /pt/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) método


Adiciona um novo efeito ao final da sequência.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objeto [IShape](../../../aspose.slides/ishape/) para adicionar um efeito |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Valor de Retorno

Novo objeto de efeito [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) método


Adiciona um novo efeito de animação para o parágrafo ao final da sequência.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objeto [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Valor de Retorno

Novo objeto de efeito [IEffect](../../ieffect/)
## Observações




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// selecionar parágrafo para adicionar efeito
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// adicionar efeito de animação Fly ao parágrafo selecionado
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) método


Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objeto Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Índice **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Valor de Retorno

Novo objeto de efeito [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) método


Adiciona o novo efeito de animação de gráfico para elementos na categoria ou série ao final da sequência.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Objeto Chart [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Tipo de um efeito de animação [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Índice da série do gráfico **int32_t** |
| categoriesIndex | **int32_t** | Índice da categoria **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo de um efeito de animação [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtipos de efeito de animação [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo de gatilho do efeito [EffectTriggerType](../../effecttriggertype/) |

### Valor de Retorno

Novo objeto de efeito [IEffect](../../ieffect/)

## Veja Também

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