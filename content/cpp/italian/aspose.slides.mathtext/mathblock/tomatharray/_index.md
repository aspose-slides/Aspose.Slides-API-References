---
title: ToMathArray()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce gli elementi figli in un array verticale
type: docs
weight: 235
url: /it/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() method


Inserisce gli elementi figli in un array verticale

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Valore di ritorno

Nuova istanza del tipo [IMathArray](../../imatharray/)
## Osservazioni



Esempio: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathArray](../../imatharray/)
* Classe [MathBlock](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)