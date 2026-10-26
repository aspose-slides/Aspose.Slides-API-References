---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट FallBack नियम को संग्रह के अंत में जोड़ें।
type: docs
weight: 40
url: /hi/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method


निर्दिष्ट FallBack नियम को संग्रह के अंत में जोड़ें।

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | जोड़ने के लिए निर्दिष्ट नियम |
## टिप्पणियाँ



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager से खाली या पूर्व-आरंभित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में नया नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [FontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)