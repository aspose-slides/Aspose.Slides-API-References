---
title: get_Superscript()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan argumen superskrip yang, misalnya, dalam kasus integral, menetapkan batas atas
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() metode

Menentukan argumen superskrip yang, misalnya, dalam kasus integral, menetapkan batas atas

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Catatan

Contoh:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)