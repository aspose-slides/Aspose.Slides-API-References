---
title: get_Limit()
second_title: Aspose.Slides per C++ Riferimento API
description: Argomento limite
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metodo

Argomento limite

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Osservazioni

Esempio: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimit](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)