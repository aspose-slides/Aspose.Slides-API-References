---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathsubscriptelement/get_base/
---
## IMathSubscriptElement::get_Base() metodo

argomento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Base()=0
```

## Osservazioni

Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathSubscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)