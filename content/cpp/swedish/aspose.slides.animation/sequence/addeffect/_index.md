---
title: AddEffect()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny effekt i slutet av sekvensen.
type: docs
weight: 157
url: /sv/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metod


Lägg till ny effekt i slutet av sekvensen.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objekt [IShape](../../../aspose.slides/ishape/) för att lägga till en effekt |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Undertyper av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metod


Lägg till ny animeringseffekt för stycke i slutet av sekvensen.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Undertyper av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)
## Anmärkningar




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

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod


Lägger till den nya diagramanimations-effekten för kategori eller serie i slutet av sekvensen.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagramobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Undertyper av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod


Lägger till den nya diagramanimations-effekten för element i kategori eller serie i slutet av sekvensen.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagramobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index för diagramserie **int32_t** |
| categoriesIndex | **int32_t** | Index för kategori **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Undertyper av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## Se även

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEffect](../../ieffect/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [Sequence](../)
* Klass [IParagraph](../../../aspose.slides/iparagraph/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)