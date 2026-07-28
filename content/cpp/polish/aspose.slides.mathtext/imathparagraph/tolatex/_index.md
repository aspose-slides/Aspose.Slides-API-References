---
title: ToLatex()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca równanie matematyczne w formacie LaTeX
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metoda


Zwraca równanie matematyczne w formacie LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IMathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)