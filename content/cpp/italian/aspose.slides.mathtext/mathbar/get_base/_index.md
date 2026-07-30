---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() metodo

Base argomento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Osservazioni

Esempio:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBar](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)