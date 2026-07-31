---
title: get_Operator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Operator Nary Contoh: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /id/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metode


Karakter Operator N-ary Untuk contoh: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Catatan


Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lihat Juga

* Kelas [MathNaryOperator](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)