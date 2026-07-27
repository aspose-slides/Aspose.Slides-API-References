---
title: get_AlignmentPoint()
second_title: Referência da API Aspose.Slides para C++
description: "Quando verdadeiro, este emulador de operador funciona como um ponto de alinhamento; ou seja, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false"
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() método

Quando verdadeiro, este emulador de operador atua como um ponto de alinhamento; ou seja, os pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Ver também

* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)