---
title: ToLatex()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'equazione matematica in formato LaTeX
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() method


Restituisce l'equazione matematica in formato LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Osservazioni


Esempio:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IMathParagraph](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)