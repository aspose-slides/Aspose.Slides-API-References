---
title: ToLatex()
second_title: Aspose.Slides برای مرجع API C++
description: معادله ریاضی را در قالب LaTeX برمی‌گرداند
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() متد

Gets mathematical equation in LaTeX format

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## نکات

Example: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## موارد دیگر

* کلاس [String](../../../system/string/)
* کلاس [IMathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)