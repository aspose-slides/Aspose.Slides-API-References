---
title: get_Superscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Apice
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() metodo


Apice

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
```

## Osservazioni


Esempio:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)