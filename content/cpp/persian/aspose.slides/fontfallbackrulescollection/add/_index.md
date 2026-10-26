---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: قانون FallBack مشخصی را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) متد

یک قاعده FallBack مشخص را به انتهای مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | قاعده مشخص برای افزودن |

## توضیحات

```cpp
auto pres = MakeObject<Presentation>();
//دریافت مجموعه قواعد خالی یا پیش‌راه‌اندازی شده از FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//افزودن قاعده جدید به مجموعه
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontFallBackRule](../../ifontfallbackrule/)
* کلاس [FontFallBackRulesCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)