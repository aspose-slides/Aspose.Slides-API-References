---
title: get_Name()
second_title: Riferimento API di Aspose.Slides per C++
description: Nome della funzione Per esempio, i nomi delle funzioni sono sin e cos
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metodo

Nome della funzione Ad esempio, i nomi delle funzioni sono sin e cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Osservazioni

Esempio: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)