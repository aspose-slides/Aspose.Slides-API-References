---
title: get_AlignmentPoint()
second_title: Referência da API Aspose.Slides para C++
description: "Quando verdadeiro, este emulador de operador atua como um ponto de alinhamento; ou seja, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false"
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() método

Quando verdadeiro, este emulador de operador atua como um ponto de alinhamento; ou seja, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Veja Também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)