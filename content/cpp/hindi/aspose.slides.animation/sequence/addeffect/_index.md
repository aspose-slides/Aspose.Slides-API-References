---
title: AddEffect()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्रम के अंत में नया प्रभाव जोड़ें।
type: docs
weight: 157
url: /hi/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) विधि


क्रम के अंत में नया प्रभाव जोड़ें।

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) ऑब्जेक्ट [IShape](../../../aspose.slides/ishape/) प्रभाव जोड़ने के लिए |
| effectType | [EffectType](../../effecttype/) | एक एनिमेशन प्रभाव का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### रिटर्न वैल्यू

नया प्रभाव ऑब्जेक्ट [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) विधि


पैराग्राफ के लिए नया एनिमेशन प्रभाव क्रम के अंत में जोड़ें।

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) ऑब्जेक्ट [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | एक एनिमेशन प्रभाव का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### रिटर्न वैल्यू

नया प्रभाव ऑब्जेक्ट [IEffect](../../ieffect/)
## टिप्पणी




```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// प्रभाव जोड़ने के लिए पैराग्राफ चुनें
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// चयनित पैराग्राफ में Fly एनिमेशन प्रभाव जोड़ें
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) विधि


श्रेणी या श्रृंखला के लिए नया चार्ट एनिमेशन प्रभाव क्रम के अंत में जोड़ता है।

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | चार्ट ऑब्जेक्ट [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | एक एनिमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | इंडेक्स **int32_t** |
| effectType | [EffectType](../../effecttype/) | एक एनिमेशन प्रभाव का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### रिटर्न वैल्यू

नया प्रभाव ऑब्जेक्ट [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) विधि


श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनिमेशन प्रभाव क्रम के अंत में जोड़ता है।

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | चार्ट ऑब्जेक्ट [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | एक एनिमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | चार्ट श्रृंखला का इंडेक्स **int32_t** |
| categoriesIndex | **int32_t** | श्रेणी का इंडेक्स **int32_t** |
| effectType | [EffectType](../../effecttype/) | एक एनिमेशन प्रभाव का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### रिटर्न वैल्यू

नया प्रभाव ऑब्जेक्ट [IEffect](../../ieffect/)

## देखें

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IEffect](../../ieffect/)
* क्लास [IShape](../../../aspose.slides/ishape/)
* क्लास [Sequence](../)
* क्लास [IParagraph](../../../aspose.slides/iparagraph/)
* क्लास [IChart](../../../aspose.slides.charts/ichart/)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)