---
title: Add()
second_title: Aspose.Slides برای مرجع API C++
description: یک قاعده FallBack جدید به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) متد

یک قاعده FallBack جدید به انتهای مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | قاعده مشخص برای افزودن |
## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قوانین خالی یا پیش‌تعیین‌شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن قاعده جدید به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [IFontFallBackRulesCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)