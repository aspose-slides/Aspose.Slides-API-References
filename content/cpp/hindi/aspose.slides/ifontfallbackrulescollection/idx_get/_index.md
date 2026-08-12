---
title: idx_get()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट अनुक्रमांक पर नियम प्राप्त करता है। केवल-पढ़ने योग्य IFontFallBackRule.
type: docs
weight: 1
url: /hi/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) विधि

निर्दिष्ट अनुक्रमांक पर नियम प्राप्त करता है। केवल-पढ़ने योग्य [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## टिप्पणियाँ

```cpp
auto pres = MakeObject<Presentation>();
//फ़ॉन्ट्समैनेजर से खाली या पहले से इनिशियलाइज़ किया गया नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में कई नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//संग्रह में पहले नियम की ऑब्जेक्ट प्राप्त करना
auto firstRule = rulesList->idx_get(0);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [IFontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)