---
title: ToLatex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يجلب المعادلة الرياضية بتنسيق LaTeX
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() طريقة

يسترجع المعادلة الرياضية بتنسيق LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## ملاحظات

مثال:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [IMathParagraph](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)