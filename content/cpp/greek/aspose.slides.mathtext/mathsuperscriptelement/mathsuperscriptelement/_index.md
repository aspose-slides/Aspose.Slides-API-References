---
title: MathSuperscriptElement()
second_title: Αναφορά API Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης MathSuperscriptElement.
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Δημιουργεί μια νέα παρουσία της [MathSuperscriptElement](../) κλάση.

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* κλάση [IMathElement](../../imathelement/)
* κλάση [MathSuperscriptElement](../)
* χώρος ονομάτων [Aspose::Slides::MathText](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)