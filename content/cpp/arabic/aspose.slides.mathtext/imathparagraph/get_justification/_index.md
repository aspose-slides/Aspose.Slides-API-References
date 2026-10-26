---
title: get_Justification()
second_title: Aspose.Slides لـ C++ مرجع API
description: "Paragraph Justification القيمة الافتراضية: CenteredAsGroup"
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() طريقة


[Paragraph](../../../aspose.slides/paragraph/) Justification القيمة الافتراضية: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
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
* فئة [IMathParagraph](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)