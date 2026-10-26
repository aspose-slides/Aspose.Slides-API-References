---
title: idx_get()
second_title: مرجع API لتقنية Aspose.Slides للغة C++
description: يحصل على القاعدة في الفهرس المحدد. للقراءة فقط IFontFallBackRule.
type: docs
weight: 1
url: /ar/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) طريقة

يحصل على القاعدة في الفهرس المحدد. للقراءة فقط [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## ملاحظات



```cpp
auto pres = MakeObject<Presentation>();
//جلب مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
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
* فئة [IFontFallBackRulesCollection](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)