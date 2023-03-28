---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides for C++ API Reference
description: Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read IFontFallBackRulesCollection.
type: docs
weight: 27
url: /cpp/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() method


Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
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
