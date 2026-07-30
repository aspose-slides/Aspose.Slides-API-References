---
title: get_Differential()
second_title: Riferimento API di Aspose.Slides per C++
description: "Differenziale. Quando vero, la casella agisce come un differenziale (ad es., \\uD835\\uDC51\\uD835\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false"
type: docs
weight: 66
url: /it/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metodo


Differenziale. Quando vero, la casella si comporta come un differenziale (ad esempio, \\uD835\\uDC51\\uDC65 in un integrando), e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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