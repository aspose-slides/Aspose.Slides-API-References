---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API संदर्भ
description: उपयोगकर्ता के FontFallBack नियमों का संग्रह दर्शाता है, जो फ़ॉन्ट्स के संग्रहों का प्रबंधन करने और फ़ॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन सुनिश्चित करने के लिए है। लिखें IFontFallBackRulesCollection.
type: docs
weight: 40
url: /hi/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) मेथड

एक उपयोगकर्ता के FontFallBack नियमों का संग्रह दर्शाता है, जो फ़ॉन्ट्स के संग्रहों का प्रबंधन करने और फ़ॉलबैक कार्यक्षमता द्वारा उचित प्रतिस्थापन सुनिश्चित करने के लिए है। लिखें [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## टिप्पणियाँ



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager से खाली या पूर्व-इनिशियलाइज़ किया गया नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// या
// नियम संग्रह की नई इंस्टेंस का इनिशियलाइज़ेशन
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// और FontsManager में मौजूदा संग्रह को नई संग्रह से बदलना
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)