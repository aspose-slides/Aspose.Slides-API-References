---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API Referansı
description: BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. True olduğunda, sınırlayıcılar oparetin yüksekliğine eşit olacak şekilde dikey olarak büyür. Varsayılan değer true'tur.
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metodu


BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. true olduğunda, sınırlayıcılar dikey olarak işaretçisinin yüksekliğine eşitlenir. Varsayılan değer true'tur.

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ayrıca Bakınız

* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)