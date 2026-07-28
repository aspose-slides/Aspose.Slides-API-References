---
title: MathLeftSubSuperscriptElement()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre a MathLeftSubSuperscriptElement osztályból.
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor

Inicializál egy új példányt a [MathLeftSubSuperscriptElement](../) osztályban.

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathLeftSubSuperscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)