---
title: MathPortion()
second_title: Referência de API do Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathPortion.
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() construtor


Inicializa uma nova instância da classe [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Veja também

* Classe [MathPortion](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)