---
title: set_Justification()
second_title: Aspose.Slides للمرجع API C++
description: "محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) طريقة


[Paragraph](../../../aspose.slides/paragraph/) محاذاة القيمة الافتراضية: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## ملاحظات


مثال:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## أنظر أيضًا

* تعداد [MathJustification](../../mathjustification/)
* فئة [IMathParagraph](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)