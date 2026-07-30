---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: L'argomento a cui è stato applicato l'accento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metodo


L'argomento a cui è stato applicato l'accento

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Osservazioni


Esempio: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)