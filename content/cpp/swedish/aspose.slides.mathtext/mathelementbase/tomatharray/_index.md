---
title: ToMathArray()
second_title: Aspose.Slides för C++ API-referens
description: Lägger in i en vertikal array
type: docs
weight: 170
url: /sv/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metod

Lägger in i en vertikal array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```

### Returvärde

Ny instans av typen [IMathArray](../../imatharray/)
## Anmärkningar

Exempel: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathArray](../../imatharray/)
* Klass [MathElementBase](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)