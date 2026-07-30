---
title: get_Differential()
second_title: Riferimento API Aspose.Slides per C++
description: "Differential Quando true, la scatola agisce come un differenziale (e.g., \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false"
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() metodo

Differential Quando true, la scatola agisce come un differenziale (e.g., \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Osservazioni

Esempio: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Vedi anche

* Classe [MathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)