---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Referansı
description: BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirler. True olduğunda, ayırıcılar yüksekliğine göre dikey olarak büyür. Varsayılan değer true'dur.
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metodu

BeginningCharacter, SeparatorCharacter, EndingCharacter öğelerinin büyümesini belirtir. True olduğunda, ayırıcılar yüksekliğine göre dikey olarak büyür. Varsayılan değer true'dur.

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Açıklamalar

Örnek:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ayrıca bakınız

* Sınıf [IMathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)