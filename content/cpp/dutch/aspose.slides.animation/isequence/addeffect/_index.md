---
title: AddEffect()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuw effect toe aan het einde van de reeks.
type: docs
weight: 144
url: /nl/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) method

Voeg een nieuw effect toe aan het einde van de reeks.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) object [IShape](../../../aspose.slides/ishape/) voor het toevoegen van een effect |
| effectType | [EffectType](../../effecttype/) | Type van een animatie-effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtype van animatie-effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger-type van effect [EffectTriggerType](../../effecttriggertype/) |

### Retourwaarde

Nieuw effectobject [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) method

Voeg een nieuw animatie-effect voor alinea toe aan het einde van de reeks.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) object [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Type van een animatie-effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtype van animatie-effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger-type van effect [EffectTriggerType](../../effecttriggertype/) |

### Retourwaarde

Nieuw effectobject [IEffect](../../ieffect/)

## Opmerkingen

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

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Voegt het nieuwe grafiek-animatie-effect toe voor categorie of serie aan het einde van de reeks.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafiekobject [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Type van een animatie-effect [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Type van een animatie-effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtype van animatie-effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger-type van effect [EffectTriggerType](../../effecttriggertype/) |

### Retourwaarde

Nieuw effectobject [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) method

Voegt het nieuwe grafiek-animatie-effect toe voor elementen in categorie of serie aan het einde van de reeks.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Grafiekobject [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Type van een animatie-effect [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index van grafiekreeks **int32_t** |
| categoriesIndex | **int32_t** | Index van categorie **int32_t** |
| effectType | [EffectType](../../effecttype/) | Type van een animatie-effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtype van animatie-effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger-type van effect [EffectTriggerType](../../effecttriggertype/) |

### Retourwaarde

Nieuw effectobject [IEffect](../../ieffect/)

## Zie ook

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