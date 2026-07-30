---
title: set_UpperLimit()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica il limite superiore o inferiore
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathlimit/set_upperlimit/
---
## MathLimit::set_UpperLimit(bool) metodo


Specifica il limite superiore o inferiore

```cpp
void Aspose::Slides::MathText::MathLimit::set_UpperLimit(bool value) override
```

## Note


Esempio: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Vedi anche

* Classe [MathLimit](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)