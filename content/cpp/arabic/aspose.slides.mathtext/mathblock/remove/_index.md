---
title: Remove()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يزيل الظهور الأول لكائن محدد من المجموعة.
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) method

يزيل الظهور الأول لكائن محدد من المجموعة.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الكائن الذي سيزيل من المجموعة. |

### قيمة الإرجاع

صحيح إذا تم إزالة *item* بنجاح من المجموعة؛ وإلا، خطأ. كما تعيد هذه الطريقة خطأ إذا لم يتم العثور على *item* في المجموعة الأصلية.

## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## انظر أيضاً

* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* مساحة_الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)