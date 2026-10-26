---
title: ToLatex()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la ecuación matemática en formato LaTeX
type: docs
weight: 183
url: /es/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() método


Obtiene la ecuación matemática en formato LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [MathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)