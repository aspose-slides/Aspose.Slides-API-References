---
title: get_Superscript()
second_title: Riferimento API Aspose.Slides per C++
description: Argomento Superscript
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_superscript/
---
## MathRightSubSuperscriptElement::get_Superscript() metodo


Argomento Superscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Superscript() override
```

## Osservazioni


Esempio:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRightSubSuperscriptElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)