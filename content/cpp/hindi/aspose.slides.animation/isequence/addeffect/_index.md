---
title: AddEffect()
second_title: Aspose.Slides for C++ API संदर्भ
description: सीक्वेंस के अंत में नया इफ़ेक्ट जोड़ें।
type: docs
weight: 144
url: /hi/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) विधि

सीक्वेंस के अंत में नया इफ़ेक्ट जोड़ें।

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) ऑब्जेक्ट [IShape](../../../aspose.slides/ishape/) इफ़ेक्ट जोड़ने के लिए |
| effectType | [EffectType](../../effecttype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन इफ़ेक्ट के सबटाइप [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | इफ़ेक्ट का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### वापसी मान

नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) विधि

सीक्वेंस के अंत में पैराग्राफ के लिए नया एनिमेशन इफ़ेक्ट जोड़ें।

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) ऑब्जेक्ट [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन इफ़ेक्ट के सबटाइप [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | इफ़ेक्ट का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### वापसी मान

नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../ieffect/)

## टिप्पणियाँ

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// इफ़ेक्ट जोड़ने के लिए पैराग्राफ चुनें
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// चुने हुए पैराग्राफ में Fly एनिमेशन इफ़ेक्ट जोड़ें
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) विधि

सीक्वेंस के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनिमेशन इफ़ेक्ट जोड़ता है।

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | चार्ट ऑब्जेक्ट [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | सूचकांक **int32_t** |
| effectType | [EffectType](../../effecttype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन इफ़ेक्ट के सबटाइप [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | इफ़ेक्ट का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### वापसी मान

नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) विधि

सीक्वेंस के अंत में श्रेणी या श्रृंखला के तत्वों के लिए नया चार्ट एनिमेशन इफ़ेक्ट जोड़ता है।

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | चार्ट ऑब्जेक्ट [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | चार्ट श्रृंखला का सूचकांक **int32_t** |
| categoriesIndex | **int32_t** | श्रेणी का सूचकांक **int32_t** |
| effectType | [EffectType](../../effecttype/) | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन इफ़ेक्ट के सबटाइप [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | इफ़ेक्ट का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### वापसी मान

नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../ieffect/)

## संबंधित

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