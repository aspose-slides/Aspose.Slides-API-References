---
title: get_Base()
second_title: Riferimento API per Aspose.Slides per C++
description: Argomento della funzione
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metodo


Argomento della funzione

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Note


Esempio: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)