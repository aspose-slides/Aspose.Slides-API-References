---
title: get_Differential()
second_title: Referência da API Aspose.Slides para C++
description: "Diferencial. Quando true, a caixa age como um diferencial (por exemplo, \\uD835\\uDC51\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false"
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() método


Diferencial. Quando true, a caixa age como um diferencial (por exemplo, \\uD835\\uDC51\\uDC65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)