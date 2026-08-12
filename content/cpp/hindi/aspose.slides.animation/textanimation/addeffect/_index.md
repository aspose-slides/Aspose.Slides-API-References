---
title: AddEffect()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान अनुक्रम के अंत में समूह टेक्स्ट एनीमेशन के अंत में नया प्रभाव जोड़ें। यह केवल तब मान्य है जब टेक्स्ट पैराग्राफ़ों की संख्या इस समूह के प्रभावों की संख्या के बराबर या अधिक हो!
type: docs
weight: 53
url: /hi/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) मेथड

नए प्रभाव को वर्तमान अनुक्रम के अंत में समूह टेक्स्ट एनीमेशन के अंत में जोड़ें। यह केवल तब वैध है जब टेक्स्ट पैराग्राफ़ की संख्या इस समूह के प्रभावों की संख्या के बराबर या अधिक हो!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | एनिमेशन प्रभाव का प्रकार [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | एनिमेशन प्रभाव के उपप्रकार [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../effecttriggertype/) |

### रिटर्न वैल्यू

नया प्रभाव ऑब्जेक्ट [IEffect](../../ieffect/)

## See Also

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IEffect](../../ieffect/)
* क्लास [TextAnimation](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)