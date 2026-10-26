---
title: Add()
second_title: مرجع API Aspose.Slides للـ C++
description: يضيف عنصرًا رياضيًا إلى نهاية المجموعة.
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) طريقة

يضيف عنصر رياضي إلى نهاية المجموعة.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) التي سيتم إضافتها إلى نهاية المجموعة. |
## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* فضاء الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)