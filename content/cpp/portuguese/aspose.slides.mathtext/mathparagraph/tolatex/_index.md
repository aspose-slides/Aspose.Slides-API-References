---
title: ToLatex()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a equação matemática no formato LaTeX
type: docs
weight: 183
url: /pt/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() método

Obtém a equação matemática no formato LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
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
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)