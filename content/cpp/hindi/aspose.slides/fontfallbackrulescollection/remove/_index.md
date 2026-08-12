---
title: Remove()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: कलेक्शन से एक विशिष्ट FallBack नियम की पहली आवृत्ति को हटाता है।
type: docs
weight: 53
url: /hi/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) मेथड

कलेक्शन से एक विशिष्ट FallBack नियम की पहली आवृत्ति को हटाता है।

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | कलेक्शन से हटाने के लिए नियम। |
## टिप्पणियाँ

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager से खाली या पहले से इनिशियलाइज़्ड नियम संग्रह प्राप्त कर रहे हैं
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//संग्रह में कई नियम जोड़ रहे हैं
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//संग्रह में पहले नियम की ऑब्जेक्ट पुनः प्राप्त कर रहे हैं
auto firstRule = rulesList->idx_get(0);
//हटा रहे हैं
rulesList->Remove(firstRule);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRule](../../ifontfallbackrule/)
* क्लास [FontFallBackRulesCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)