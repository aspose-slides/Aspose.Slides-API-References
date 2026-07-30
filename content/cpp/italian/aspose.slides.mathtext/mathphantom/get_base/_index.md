---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() metodo

argomento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathPhantom](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)