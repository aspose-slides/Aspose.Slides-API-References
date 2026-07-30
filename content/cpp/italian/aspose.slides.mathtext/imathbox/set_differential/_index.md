---
title: set_Differential()
second_title: Riferimento API Aspose.Slides per C++
description: "Differenziale. Quando è vero, il riquadro funziona come un differenziale (ad esempio, \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false"
type: docs
weight: 79
url: /it/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) metodo

Differenziale. Quando è vero, il contenitore si comporta come un differenziale (ad esempio, \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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

* Classe [IMathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)