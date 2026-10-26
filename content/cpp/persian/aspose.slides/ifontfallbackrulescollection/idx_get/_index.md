---
title: idx_get()
second_title: Aspose.Slides برای مرجع API C++
description: قانون را در ایندکس مشخص دریافت می‌کند. فقط خواندنی IFontFallBackRule.
type: docs
weight: 1
url: /fa/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) متد


قانون را در ایندکس مشخص دریافت می‌کند. فقط خواندنی [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## توضیحات



```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قوانین خالی یا پیش‌راه‌اندازی شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن چندین قانون به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//دریافت شیء اولین قانون در مجموعه
auto firstRule = rulesList->idx_get(0);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [IFontFallBackRulesCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)