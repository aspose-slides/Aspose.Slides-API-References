---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف IMathBlock إلى نهاية المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) طريقة

يضيف [IMathBlock](../../imathblock/) إلى نهاية المجموعة.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | كتلة رياضية سيتم إضافتها إلى نهاية المجموعة |
## ملاحظات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathBlockCollection](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)