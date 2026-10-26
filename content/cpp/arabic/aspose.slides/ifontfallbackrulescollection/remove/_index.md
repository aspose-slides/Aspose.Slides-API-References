---
title: Remove()
second_title: Aspose.Slides للغة C++ مرجع API
description: يزيل الظهور الأول لقاعدة FallBack محددة من المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) طريقة

يقوم بإزالة الظهور الأول لقاعدة FallBack محددة من المجموعة.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | القاعدة التي سيتم إزالتها من المجموعة. |
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
* فئة [IFontFallBackRulesCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)