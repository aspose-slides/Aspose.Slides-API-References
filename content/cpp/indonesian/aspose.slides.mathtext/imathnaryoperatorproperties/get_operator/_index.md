---
title: get_Operator()
second_title: Aspose.Slides untuk Referensi API C++
description: "Karakter Operator Nary Misalnya: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metode

Karakter Operator Nary Misalnya: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Keterangan

Contoh:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lihat Juga

* Kelas [IMathNaryOperatorProperties](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)