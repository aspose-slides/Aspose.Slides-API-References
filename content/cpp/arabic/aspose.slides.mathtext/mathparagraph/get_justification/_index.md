---
title: get_Justification()
second_title: مرجع API Aspose.Slides للغة C++
description: "Paragraph Justification القيمة الافتراضية: CenteredAsGroup"
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() طريقة

[Paragraph](../../../aspose.slides/paragraph/) Justification القيمة الافتراضية: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```
## ملاحظات

مثال: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## انظر أيضًا

* تعداد [MathJustification](../../mathjustification/)
* فئة [MathParagraph](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)