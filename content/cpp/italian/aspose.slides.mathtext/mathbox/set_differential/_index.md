---
title: set_Differential()
second_title: Riferimento API di Aspose.Slides per C++
description: "Differenziale Quando è true, la casella agisce come un differenziale (ad es., \\uD835\\uDC51\\uD835\\uDC65 in un integrando) e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false"
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) method

Differential Se è true, la casella agisce come un differenziale (ad es., \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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