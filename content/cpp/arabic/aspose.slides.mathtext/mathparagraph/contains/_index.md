---
title: Contains()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) طريقة


يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الكائن المراد تحديد موقعه في المجموعة. |

### قيمة الإرجاع

true إذا تم العثور على *mathBlock* في المجموعة؛ وإلا، false.
## ملاحظات



مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## انظر أيضًا

* نوع تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)