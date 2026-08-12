---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ॉन्ट फ़ॉलबैक नियमों के उपयोगकर्ता संग्रह का प्रतिनिधित्व करता है, जो फ़ॉन्ट्स के संग्रहों को प्रबंधित करने और फ़ॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन सुनिश्चित करने के लिए है। पढ़ें IFontFallBackRulesCollection.
type: docs
weight: 27
url: /hi/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() मेथड

FontFallBack नियमों का उपयोगकर्ता संग्रह प्रस्तुत करता है, जो फ़ॉन्ट्स के संग्रहों को प्रबंधित करता है ताकि फॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन हो सके। पढ़ें [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## टिप्पणी


```cpp
auto pres = MakeObject<Presentation>();
// FontsManager से खाली या पूर्व-आरम्भित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// या
// नियम संग्रह की नई इंस्टेंस को इनिशियलाइज़ करना
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// और FontsManager में मौजूदा संग्रह को नई संग्रह से बदलना
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* क्लास [IFontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)