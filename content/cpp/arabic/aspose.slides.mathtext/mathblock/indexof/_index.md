---
title: IndexOf()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد فهرس عنصر رياضي محدد في المجموعة.
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathblock/indexof/
---
## طريقة MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) method

يحدد فهرس عنصر رياضي محدد في المجموعة.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الذي يجب العثور عليه في المجموعة. |

### قيمة الإرجاع

فهرس *item* إذا تم العثور عليه في المجموعة؛ وإلا، -1.
## ملاحظات



مثال:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* مساحة أسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)