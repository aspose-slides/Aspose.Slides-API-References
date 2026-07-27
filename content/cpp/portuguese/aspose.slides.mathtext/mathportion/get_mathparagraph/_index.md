---
title: get_MathParagraph()
second_title: Aspose.Slides para C++ Referência da API
description: Parágrafo matemático
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathportion/get_mathparagraph/
---
## MathPortion::get_MathParagraph() método


Parágrafo matemático

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathPortion::get_MathParagraph() override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathParagraph](../../imathparagraph/)
* Classe [MathPortion](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)