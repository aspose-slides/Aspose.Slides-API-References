---
title: set_FontFallBackRulesCollection()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش‌دهندهٔ مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت‌ها به منظور جایگزینی صحیح توسط عملکرد fallback. بنویسید IFontFallBackRulesCollection.
type: docs
weight: 40
url: /fa/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) متد

نمایش‌دهندهٔ مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های فونت‌ها به‌منظور جایگزینی مناسب توسط عملکرد fallback. بنویسید [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## یادداشت‌ها

```cpp
auto pres = MakeObject<Presentation>();
// دریافت مجموعهٔ خالی یا پیش‌راه‌اندازی‌شدهٔ قوانین از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// افزودن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// یا
// راه‌اندازی یک نمونهٔ جدید از مجموعهٔ قوانین
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// افزودن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// و جایگزینی مجموعهٔ موجود با مجموعهٔ جدید در FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* کلاس [FontsManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)