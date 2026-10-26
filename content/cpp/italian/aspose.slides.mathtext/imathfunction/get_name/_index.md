---
title: get_Name()
second_title: Riferimento API di Aspose.Slides per C++
description: Nome della funzione. Ad esempio, i nomi delle funzioni sono sin e cos
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() metodo

Nome della funzione Ad esempio, i nomi delle funzioni sono sin e cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
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
* Classe [IMathFunction](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)