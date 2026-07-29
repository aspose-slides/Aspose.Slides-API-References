---
title: ToMathArray()
second_title: Aspose.Slides för C++ API-referens
description: Sätter in i en vertikal matris
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metod


Sätter in i en vertikal matris

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Returvärde

Ny instans av typen [IMathArray](../../imatharray/)
## Anmärkningar


Exempel:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathArray](../../imatharray/)
* Klass [IMathElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)