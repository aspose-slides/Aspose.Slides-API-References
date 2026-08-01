---
title: ToLatex()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt wiskundige vergelijking op in LaTeX-indeling
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() methode


Haalt wiskundige vergelijking op in LaTeX-indeling

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
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
* Klasse [IMathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)