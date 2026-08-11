---
title: Clear()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل جميع العناصر من المجموعة.
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() طريقة


يقوم بإزالة جميع العناصر من المجموعة.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## ملاحظات


مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## انظر أيضًا

* الفئة [MathParagraph](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)