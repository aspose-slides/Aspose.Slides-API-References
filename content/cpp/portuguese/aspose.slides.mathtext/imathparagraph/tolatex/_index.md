---
title: ToLatex()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém a equação matemática no formato LaTeX
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() método


Obtém a equação matemática no formato LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Veja também

* Classe [String](../../../system/string/)
* Classe [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)