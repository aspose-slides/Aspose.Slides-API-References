---
title: ToLatex()
second_title: Aspose.Slides for C++ API Reference
description: Gets mathematical equation in LaTeX format
type: docs
weight: 40
url: /aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() method


Gets mathematical equation in LaTeX format

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<Aspose::Slides::MathText::MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## See Also

* Class [String](../../../system/string/)
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)