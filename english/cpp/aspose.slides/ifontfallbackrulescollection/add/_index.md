---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Add a new FallBack rule to the end of the collection.
type: docs
weight: 14
url: /cpp/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add([System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\>) method


Add a new FallBack rule to the end of the collection.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Specified rule for adding |
## Remarks



```cpp
auto pres = MakeObject<Presentation>();
//Getting of empty or preinitialized rules collection from FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Adding of new rule to collection
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRule](../../ifontfallbackrule/)
* Class [IFontFallBackRulesCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
