---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Gets the rule at the specified index. Read-only IFontFallBackRule.
type: docs
weight: 66
url: /cpp/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) method


Gets the rule at the specified index. Read-only [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Remarks



```cpp
auto pres = MakeObject<Presentation>();
//Getting of empty or preinitialized rules collection from FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Adding of several rules to collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Retrieving of object of the first rule in collection
auto firstRule = rulesList->idx_get(0);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [FontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)