---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: उपयोगकर्ता द्वारा फ़ॉन्ट फ़ॉलबैक नियमों का संग्रह दर्शाता है, जो फ़ॉन्ट संग्रह को उचित प्रतिस्थापन के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करने हेतु उपयोग होता है। Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /hi/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) विधि

उपयोगकर्ता द्वारा फ़ॉन्ट फ़ॉलबैक नियमों का संग्रह दर्शाता है, जिसका उपयोग फ़ॉन्ट संग्रह को उचित प्रतिस्थापन के लिए फ़ॉलबैक कार्यक्षमता द्वारा प्रबंधित करने हेतु किया जाता है। लिखें [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)।

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## टिप्पणियाँ

```cpp
auto pres = MakeObject<Presentation>();
// FontsManager से खाली या पूर्व-प्रारंभित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// या
// नियम संग्रह के नए उदाहरण का प्रारंभिकरण
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// FontsManager में मौजूदा संग्रह को नए द्वारा बदलना
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* क्लास [FontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)