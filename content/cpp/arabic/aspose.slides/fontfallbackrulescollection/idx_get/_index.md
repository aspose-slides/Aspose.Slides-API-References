---
title: idx_get()
second_title: Aspose.Slides for C++ مرجع API
description: يسترجع القاعدة في الفهرس المحدد. قراءة فقط IFontFallBackRule.
type: docs
weight: 66
url: /ar/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) طريقة

يسترجع القاعدة في الفهرس المحدد. قراءة فقط [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
//الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//إضافة عدة قواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//استرجاع كائن القاعدة الأولى في المجموعة
auto firstRule = rulesList->idx_get(0);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRule](../../ifontfallbackrule/)
* فئة [FontFallBackRulesCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)