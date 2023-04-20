---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the first occurrence of a specific FallBack rule from the collection.
type: docs
weight: 53
url: /cpp/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) method


Removes the first occurrence of a specific FallBack rule from the collection.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | The rule to remove from the collection. |
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
//Removing
rulesList->Remove(firstRule);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [FontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)