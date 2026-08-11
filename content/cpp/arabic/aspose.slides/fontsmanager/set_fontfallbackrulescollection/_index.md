---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة التعويض اكتب IFontFallBackRulesCollection.
type: docs
weight: 40
url: /ar/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) طريقة

يمثّل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة عبر وظيفة التعويض اكتب [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
// جلب مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// إضافة القواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// أو
// تهيئة نسخة جديدة من مجموعة القواعد
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// إضافة القواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// واستبدال المجموعة الموجودة بالجديدة في FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* فئة [FontsManager](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)