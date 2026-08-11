---
title: Remove()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يزيل الظهور الأول لقاعدة FallBack معينة من المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) طريقة

يزيل الظهور الأول لقاعدة FallBack معينة من المجموعة.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | القاعدة التي يجب إزالتها من المجموعة. |

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
//إزالة
rulesList->Remove(firstRule);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRule](../../ifontfallbackrule/)
* فئة [FontFallBackRulesCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)