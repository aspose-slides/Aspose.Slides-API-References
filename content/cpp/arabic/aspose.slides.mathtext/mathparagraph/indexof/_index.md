---
title: IndexOf()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد فهرس كائن IMathBlock معين في المجموعة.
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) طريقة

يحدد فهرس عنصر [IMathBlock](../../imathblock/) محدد في المجموعة.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### المعلمات
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | العنصر المطلوب العثور عليه في المجموعة. |

### قيمة الإرجاع
فهرس *mathBlock* إذا وُجد في المجموعة؛ وإلا -1.

## ملاحظات



مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## انظر أيضًا
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [MathParagraph](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)