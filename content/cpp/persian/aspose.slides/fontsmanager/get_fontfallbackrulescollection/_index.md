---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر مجموعه‌ای از قوانین FontFallBack کاربر برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی‌های صحیح توسط عملکرد fallback. خوانید IFontFallBackRulesCollection.
type: docs
weight: 27
url: /fa/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() متد

مجموعه‌ای از قوانین FontFallBack کاربر را برای مدیریت مجموعه‌های قلم‌ها به‌منظور تعویض‌های صحیح توسط عملکرد fallback نشان می‌دهد. خوانید [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## توضیحات


```cpp
auto pres = MakeObject<Presentation>();
// دریافت مجموعه خالی یا پیش‌مقداردهی شده قوانین از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// اضافه کردن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// یا
// ایجاد نمونه جدیدی از مجموعه قوانین
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// اضافه کردن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// و جایگزینی مجموعه موجود با مجموعه جدید در FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* کلاس [FontsManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)