---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metodo


argomento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)