---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر مجموعه‌ای از قواعد FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی‌های صحیح توسط عملکرد fallback است. نوشتن IFontFallBackRulesCollection.
type: docs
weight: 40
url: /fa/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) متد

نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به‌منظور جایگزینی‌های صحیح توسط عملکرد fallback است. نوشتن [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## توضیحات

```cpp
auto pres = MakeObject<Presentation>();
// دریافت مجموعه قوانین خالی یا پیش‌راه‌اندازی‌شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// افزودن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// یا
// راه‌اندازی نمونه جدیدی از مجموعه قوانین
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// افزودن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// و جایگزینی مجموعه موجود با مجموعه جدید در FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* کلاس [IFontsManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)