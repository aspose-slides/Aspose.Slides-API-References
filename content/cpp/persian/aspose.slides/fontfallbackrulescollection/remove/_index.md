---
title: Remove()
second_title: مرجع API Aspose.Slides برای C++
description: اولین رخداد یک قاعده FallBack خاص را از مجموعه حذف می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) متد

اولین رخداد یک قاعده FallBack خاص را از مجموعه حذف می‌کند.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | قاعده‌ای که باید از مجموعه حذف شود. |
## یادداشت‌ها

```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قوانین خالی یا از پیش مقداردهی شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن چندین قاعده به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//دریافت شیء اولین قاعده در مجموعه
auto firstRule = rulesList->idx_get(0);
//حذف
rulesList->Remove(firstRule);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [FontFallBackRulesCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)