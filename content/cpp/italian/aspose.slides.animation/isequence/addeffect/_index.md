---
title: AddEffect()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un nuovo effetto alla fine della sequenza.
type: docs
weight: 144
url: /it/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metodo


Aggiunge un nuovo effetto alla fine della sequenza.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) oggetto [IShape](../../../aspose.slides/ishape/) per aggiungere un effetto |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi di effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di attivazione dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetti [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metodo


Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) oggetto [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi di effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di attivazione dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetti [IEffect](../../ieffect/)
## Osservazioni




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// seleziona il paragrafo per aggiungere l'effetto
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// aggiungi l'effetto di animazione Fly al paragrafo selezionato
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metodo


Aggiunge il nuovo effetto di animazione del grafico per categoria o serie alla fine della sequenza.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Oggetto grafico [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Tipo di un effetto di animazione [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Indice **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi di effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di attivazione dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetti [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metodo


Aggiunge il nuovo effetto di animazione del grafico per elementi in categoria o serie alla fine della sequenza.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Oggetto grafico [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Tipo di un effetto di animazione [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Indice della serie del grafico **int32_t** |
| categoriesIndex | **int32_t** | Indice della categoria **int32_t** |
| effectType | [EffectType](../../effecttype/) | Tipo di un effetto di animazione [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Sottotipi di effetto di animazione [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Tipo di attivazione dell'effetto [EffectTriggerType](../../effecttriggertype/) |

### Valore di ritorno

Nuovo oggetto effetti [IEffect](../../ieffect/)

## Vedi anche

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