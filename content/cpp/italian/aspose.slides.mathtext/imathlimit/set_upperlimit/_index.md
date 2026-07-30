---
title: set_UpperLimit()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica il limite superiore o inferiore
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) metodo


Specifica il limite superiore o inferiore

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Osservazioni


Esempio: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Vedi anche

* Classe [IMathLimit](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)