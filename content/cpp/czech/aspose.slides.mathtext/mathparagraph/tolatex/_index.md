---
title: ToLatex()
second_title: Aspose.Slides pro C++ API Reference
description: Získá matematickou rovnici ve formátu LaTeX
type: docs
weight: 183
url: /cs/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() metoda


Získá matematickou rovnici ve formátu LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
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
* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)