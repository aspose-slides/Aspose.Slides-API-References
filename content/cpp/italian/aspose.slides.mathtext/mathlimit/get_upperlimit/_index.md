---
title: get_UpperLimit()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica il limite superiore o inferiore
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() metodo


Specifica il limite superiore o inferiore

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Osservazioni


Esempio: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Vedi anche

* Classe [MathLimit](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)