---
title: set_Operator()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Operator Nary Misalnya: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /id/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) metode


Karakter Operator Nary Misalnya: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Keterangan


Contoh: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Lihat Juga

* Kelas [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)