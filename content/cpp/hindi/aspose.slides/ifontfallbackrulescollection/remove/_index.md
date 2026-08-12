---
title: Remove()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कलेक्शन से एक विशिष्ट FallBack नियम की पहली उपस्थिति को हटाता है।
type: docs
weight: 27
url: /hi/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) विधि


कलेक्शन से एक विशिष्ट FallBack नियम की पहली उपस्थिति को हटाता है।

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | कलेक्शन से हटाने के लिए नियम। |
## टिप्पणियाँ



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager से खाली या पूर्व-आरम्भित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में कई नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//संग्रह में पहले नियम की ऑब्जेक्ट प्राप्त करना
auto firstRule = rulesList->idx_get(0);
//हटाना
rulesList->Remove(firstRule);
```


## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [IFontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)