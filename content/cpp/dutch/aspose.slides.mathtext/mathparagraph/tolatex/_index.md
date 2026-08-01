---
title: ToLatex()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een wiskundige vergelijking op in LaTeX-indeling
type: docs
weight: 183
url: /nl/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() methode


Haalt een wiskundige vergelijking op in LaTeX-indeling

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [MathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)