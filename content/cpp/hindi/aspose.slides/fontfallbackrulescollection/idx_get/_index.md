---
title: idx_get()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट सूचकांक पर नियम प्राप्त करता है। केवल पढ़ने योग्य IFontFallBackRule.
type: docs
weight: 66
url: /hi/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) विधि

निर्दिष्ट सूचकांक पर नियम प्राप्त करता है। केवल-पढ़ने योग्य [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## टिप्पणियाँ

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager से खाली या पूर्व-प्रारम्भित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में कई नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//संग्रह में पहले नियम की वस्तु प्राप्त करना
auto firstRule = rulesList->idx_get(0);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [FontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)