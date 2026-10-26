---
title: get_Base()
second_title: Referensi API Aspose.Slides untuk C++
description: Argumen Base
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() metode

Argumen Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Catatan

Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathNaryOperator](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)