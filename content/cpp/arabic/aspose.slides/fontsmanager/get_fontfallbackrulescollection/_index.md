---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات المناسبة عبر وظيفة التعويض. اقرأ IFontFallBackRulesCollection.
type: docs
weight: 27
url: /ar/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() طريقة

يمثل مجموعة المستخدم من قواعد FontFallBack لإدارة مجموعات الخطوط للاستبدالات الصحيحة بواسطة وظيفة التعويض. اقرأ [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## ملاحظات



```cpp
auto pres = MakeObject<Presentation>();
// جلب مجموعة القواعد الفارغة أو المهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// إضافة قواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// أو
// تهيئة نسخة جديدة من مجموعة القواعد
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// إضافة قواعد إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// واستبدال المجموعة الحالية بالمجموعة الجديدة في FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* فئة [FontsManager](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)