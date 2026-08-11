---
title: Remove()
second_title: Aspose.Slides برای C++ مرجع API
description: اولین رخداد یک قاعده FallBack خاص را از مجموعه حذف می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) متد

اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | قاعده‌ای که باید از مجموعه حذف شود. |
## نکات



```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قوانین خالی یا از پیش مقداردهی شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن چندین قانون به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//دریافت شیء اولین قانون در مجموعه
auto firstRule = rulesList->idx_get(0);
//حذف
rulesList->Remove(firstRule);
```


## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [IFontFallBackRulesCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)