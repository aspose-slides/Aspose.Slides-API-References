---
title: set_Operator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Operator Nary Contoh: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) metode

Karakter Operator Nary Contoh: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
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
* Pustaka [Aspose.Slides](../../../)