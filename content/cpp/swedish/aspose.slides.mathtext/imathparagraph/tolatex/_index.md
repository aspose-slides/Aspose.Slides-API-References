---
title: ToLatex()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar matematisk ekvation i LaTeX-format
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metod


Hämtar matematisk ekvation i LaTeX-format

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IMathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)