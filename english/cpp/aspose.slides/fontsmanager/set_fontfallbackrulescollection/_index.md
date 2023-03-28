---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API Reference
description: Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /cpp/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection([System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)\>) method


Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Remarks



```cpp
auto pres = MakeObject<Presentation>();
// Getting of empty or preinitialized rules collection from FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// adding of rules to collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// or
// initialization of new instance of rules collection
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// adding of rules to collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// and replacing of existing collection by the new one in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
