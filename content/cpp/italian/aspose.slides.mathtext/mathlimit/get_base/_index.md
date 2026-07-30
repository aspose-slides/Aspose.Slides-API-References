---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() metodo

Argomento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Osservazioni

Esempio: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)