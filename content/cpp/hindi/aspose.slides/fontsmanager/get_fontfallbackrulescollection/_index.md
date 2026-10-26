---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ॉन्टफ़ॉलबैक नियमों का उपयोगकर्ता संग्रह दर्शाता है, जो फ़ॉन्ट संग्रहों के प्रबंधन के लिए उपयुक्त प्रतिस्थापन को fallback कार्यक्षमता द्वारा सुनिश्चित करता है। पढ़ें IFontFallBackRulesCollection.
type: docs
weight: 27
url: /hi/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() विधि


यह FontFallBack नियमों का उपयोगकर्ता संग्रह दर्शाता है, जो फ़ॉन्ट संग्रहों का प्रबंधन करके fallback कार्यक्षमता द्वारा उचित प्रतिस्थापन सुनिश्चित करता है। पढ़ें [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## टिप्पणियाँ



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager से खाली या पूर्व-प्रारंभित नियम संग्रह प्राप्त करना
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// या
// नियम संग्रह का नया उदाहरण आरंभ करना
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// संग्रह में नियम जोड़ना
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// और FontsManager में मौजूदा संग्रह को नए संग्रह से बदलना
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* क्लास [FontsManager](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)