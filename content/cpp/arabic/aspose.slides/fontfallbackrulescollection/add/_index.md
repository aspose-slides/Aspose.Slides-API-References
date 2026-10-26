---
title: Add()
second_title: Aspose.Slides للـ C++ مرجع API
description: أضف قاعدة FallBack محددة إلى نهاية المجموعة.
type: docs
weight: 40
url: /ar/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) طريقة

أضف قاعدة FallBack محددة إلى نهاية المجموعة.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | القاعدة المحددة للإضافة |
## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
//الحصول على مجموعة القواعد الفارغة أو المهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//إضافة قاعدة جديدة إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRule](../../ifontfallbackrule/)
* فئة [FontFallBackRulesCollection](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)