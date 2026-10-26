---
title: ToMathArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce in un array verticale
type: docs
weight: 170
url: /it/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metodo


Inserisce in un array verticale

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
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
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)