---
title: ToMathArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce in un array verticale
type: docs
weight: 183
url: /it/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metodo


Inserisce in un array verticale

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
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
* Classe [IMathElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)