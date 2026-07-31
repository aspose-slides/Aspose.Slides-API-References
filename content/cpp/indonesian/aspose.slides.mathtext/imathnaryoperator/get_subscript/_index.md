---
title: get_Subscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() metode

Menentukan argumen subskrip yang, misalnya, dalam kasus integral, menetapkan batas bawah

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
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
* Kelas [IMathNaryOperator](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)