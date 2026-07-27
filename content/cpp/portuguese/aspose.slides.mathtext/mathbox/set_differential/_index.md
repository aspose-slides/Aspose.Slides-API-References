---
title: set_Differential()
second_title: Referência da API Aspose.Slides para C++
description: "Differential Quando true, a caixa atua como um diferencial (por exemplo, \\uD835\\uDC51\\uD835\\uDC65 em um integrando), e recebe o espaçamento horizontal adequado para o diferencial matemático. Padrão: false"
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) método

Differential Quando true, a caixa atua como um diferencial (por exemplo, \\uD835\\uDC51\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Observações


Exemplo:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Veja também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)