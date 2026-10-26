---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Referansı
description: BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. true olduğunda, sınırlayıcılar operand yüksekliğine göre dikey olarak büyür. Varsayılan değer true'tir.
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metodu


BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. true olduğunda, sınırlayıcılar operand yüksekliğine göre dikey olarak büyür. Varsayılan değer true'tir.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ayrıca Bakınız

* Sınıf [MathDelimiter](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)