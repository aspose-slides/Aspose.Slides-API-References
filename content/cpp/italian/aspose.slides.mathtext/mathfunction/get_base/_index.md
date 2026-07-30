---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento della funzione
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metodo

Argomento della funzione

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Osservazioni

Esempio: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)