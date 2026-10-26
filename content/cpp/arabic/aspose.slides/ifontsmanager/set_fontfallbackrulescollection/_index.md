---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides لمرجع API لـ C++
description: يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط من أجل الاستبدالات المناسبة عبر وظيفة fallback. اكتب IFontFallBackRulesCollection.
type: docs
weight: 40
url: /ar/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) طريقة

يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط من أجل الاستبدالات المناسبة عبر وظيفة fallback اكتب [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## ملاحظات



```cpp
auto pres = MakeObject<Presentation>();
// الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// إضافة القواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// أو
// تهيئة نسخة جديدة من مجموعة القواعد
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// إضافة القواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// واستبدال المجموعة الحالية بالجديدة في FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* فئة [IFontsManager](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)