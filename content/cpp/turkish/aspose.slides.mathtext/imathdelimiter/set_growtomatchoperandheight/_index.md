---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Referansı
description: BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. true olduğunda, ayırıcılar yüksekliğine uyması için dikey olarak büyür. Varsayılan değer true'dur.
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metod

BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. true olduğunda, ayırıcılar yüksekliğine uyması için dikey olarak büyür. Varsayılan değer true'dur.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Bakınız

* Sınıf [IMathDelimiter](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)