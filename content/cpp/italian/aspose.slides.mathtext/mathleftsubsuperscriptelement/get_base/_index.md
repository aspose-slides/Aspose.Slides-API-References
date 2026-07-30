---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: argomento Base
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() metodo


argomento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Osservazioni


Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLeftSubSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)