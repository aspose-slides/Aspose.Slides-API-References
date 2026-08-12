---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में एक नया FallBack नियम जोड़ें।
type: docs
weight: 14
url: /hi/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) विधि

संग्रह के अंत में एक नया FallBack नियम जोड़ें।

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | जोड़ने के लिए निर्दिष्ट नियम |
## टिप्पणी



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager से खाली या पहले से इनिशियलाइज़्ड नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में नया नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [IFontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)