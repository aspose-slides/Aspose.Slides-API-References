---
title: ToLatex()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Pobiera równanie matematyczne w formacie LaTeX
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() metoda


Pobiera równanie matematyczne w formacie LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
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
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)