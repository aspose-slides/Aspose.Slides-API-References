---
title: ToLatex()
second_title: Aspose.Slides برای مرجع API C++
description: معادله ریاضی را در قالب LaTeX دریافت می‌کند
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() متد


معادله ریاضی را در قالب LaTeX دریافت می‌کند

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## توضیحات


مثال: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [MathParagraph](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)