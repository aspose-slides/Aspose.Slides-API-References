---
title: get_FontFallBackRulesCollection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. اقرأ IFontFallBackRulesCollection.
type: docs
weight: 27
url: /ar/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() طريقة

يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة fallback. اقرأ [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
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

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* فئة [IFontsManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)