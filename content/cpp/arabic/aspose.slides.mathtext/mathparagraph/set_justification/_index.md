---
title: set_Justification()
second_title: Aspose.Slides للـ C++ مرجع API
description: "محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) طريقة


[Paragraph](../../../aspose.slides/paragraph/) Justification القيمة الافتراضية: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)