---
title: ToLatex()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على المعادلة الرياضية بصيغة LaTeX
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() طريقة


يُحصل على المعادلة الرياضية بصيغة LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
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

* الفئة [String](../../../system/string/)
* الفئة [MathParagraph](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)