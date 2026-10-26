---
title: get_Differential()
second_title: Referência da API Aspose.Slides para C++
description: "Differential Quando true, a caixa atua como um diferencial (e.g., \\uD835\\uDC51\\uD835\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false"
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() método


Differential Quando true, a caixa atua como um diferencial (e.g., \\uD835\\uDC51\\uD835\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Observações


Exemplo: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Ver também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)