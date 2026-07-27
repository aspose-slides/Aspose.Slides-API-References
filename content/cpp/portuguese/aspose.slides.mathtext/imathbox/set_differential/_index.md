---
title: set_Differential()
second_title: Aspose.Slides para C++ Referência da API
description: "Diferencial. Quando true, a caixa atua como um diferencial (por exemplo, \\uD835\\uDC51\\uD835\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false"
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) method

Diferencial. Quando true, a caixa atua como um diferencial (por exemplo, \\uD835\\uDC51\\uD835\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Observações


Exemplo: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Veja Também

* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)