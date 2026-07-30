---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() metodo


Base argomento

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
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
* Classe [IMathLeftSubSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)