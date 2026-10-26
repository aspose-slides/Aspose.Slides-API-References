---
title: ToLatex()
second_title: Aspose.Slides pro C++ referenci API
description: Získá matematickou rovnici ve formátu LaTeX
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metoda


Získá matematickou rovnici ve formátu LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IMathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)