---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای از قوانین FontFallBack کاربر را برای مدیریت مجموعه‌های قلم‌ها به‌منظور جایگزینی صحیح توسط عملکرد بازگشت ارائه می‌دهد. مطالعه کنید IFontFallBackRulesCollection.
type: docs
weight: 27
url: /fa/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() متد


مجموعهٔ قوانین FontFallBack کاربر را برای مدیریت مجموعه‌های قلم‌ها به منظور جایگزینی صحیح توسط عملکرد بازگشت نشان می‌دهد. مطالعه کنید [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## ملاحظات



```cpp
auto pres = MakeObject<Presentation>();
// دریافت مجموعهٔ قوانین خالی یا پیش‌مقداردهی شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// اضافه کردن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// یا
// ایجاد نمونهٔ جدید از مجموعهٔ قوانین
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// اضافه کردن قوانین به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// و جایگزینی مجموعهٔ موجود با مجموعهٔ جدید در FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* کلاس [IFontsManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)