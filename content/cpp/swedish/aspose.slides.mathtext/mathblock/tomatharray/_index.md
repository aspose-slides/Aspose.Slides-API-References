---
title: ToMathArray()
second_title: Aspose.Slides för C++ API-referens
description: Sätter underordnade element i en vertikal matris
type: docs
weight: 235
url: /sv/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metod

Sätter underordnade element i en vertikal matris

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### Returvärde

Ny instans av typen [IMathArray](../../imatharray/)
## Anmärkningar



Exempel: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathArray](../../imatharray/)
* Klass [MathBlock](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)