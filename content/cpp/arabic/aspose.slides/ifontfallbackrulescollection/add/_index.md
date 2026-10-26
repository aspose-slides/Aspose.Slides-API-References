---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: أضف قاعدة FallBack جديدة إلى نهاية المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) طريقة

أضف قاعدة FallBack جديدة إلى نهاية المجموعة.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | القاعدة المحددة للإضافة |
## ملاحظات



```cpp
auto pres = MakeObject<Presentation>();
//الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقًا من FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//إضافة قاعدة جديدة إلى المجموعة
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontFallBackRule](../../ifontfallbackrule/)
* فئة [IFontFallBackRulesCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)