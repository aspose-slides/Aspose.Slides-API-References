---
title: ToLatex()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert mathematische Gleichung im LaTeX-Format
type: docs
weight: 183
url: /de/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() Methode


Liefert mathematische Gleichung im LaTeX-Format

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [MathParagraph](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)