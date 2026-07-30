---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() metodo


Argomento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Osservazioni


Esempio: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // radice cubica
auto baseElem = radical->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRadical](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)