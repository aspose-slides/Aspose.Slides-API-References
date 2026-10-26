---
title: get_Subscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() metode

Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Catatan

Contoh:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathNaryOperator](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)