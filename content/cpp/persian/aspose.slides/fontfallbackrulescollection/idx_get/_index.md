---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: قانون را در ایندکس مشخص دریافت می‌کند. فقط خواندنی IFontFallBackRule.
type: docs
weight: 66
url: /fa/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) متد

قواعد را در ایندکس مشخص دریافت می‌کند. فقط خواندنی [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## توضیحات

```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قوانین خالی یا پیش‌نقش‌گذاری شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن چندین قانون به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//دریافت شیء اولین قانون در مجموعه
auto firstRule = rulesList->idx_get(0);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [FontFallBackRulesCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)