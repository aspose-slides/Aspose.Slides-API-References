---
title: AddEffect()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny effekt i slutet av sekvensen.
type: docs
weight: 144
url: /sv/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) metod

Lägg till en ny effekt i slutet av sekvensen.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) objekt [IShape](../../../aspose.slides/ishape/) för att lägga till en effekt |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Underkategorier av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) metod

Lägg till en ny animeringseffekt för stycket i slutet av sekvensen.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) objekt [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Underkategorier av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## Anmärkningar

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// välj stycke för att lägga till effekt
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// lägg till Fly-animeringseffekt till valt stycke
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod

Lägger till den nya diagramanimeringseffekten för kategori eller serie i slutet av sekvensen.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagramobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | Index **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Underkategorier av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) metod

Lägger till den nya diagramanimeringseffekten för element i kategori eller serie i slutet av sekvensen.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | Diagramobjekt [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | Index för diagramserie **int32_t** |
| categoriesIndex | **int32_t** | Index för kategori **int32_t** |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Underkategorier av animeringseffekt [EffectSubtype](../../effectsubtype/) |
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
* Klass [ISequence](../)
* Klass [IParagraph](../../../aspose.slides/iparagraph/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)