---
title: Contains()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) طريقة


يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الكائن لتحديد موقعه في المجموعة. |

### قيمة الإرجاع

صحيح إذا تم العثور على *item* في المجموعة؛ وإلا، خطأ.
## ملاحظات



مثال: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)