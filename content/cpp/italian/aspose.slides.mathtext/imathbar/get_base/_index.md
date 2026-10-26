---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Base argomento
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() metodo


Base argomento

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Note


Esempio: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBar](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)