---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Ending Character bitiş ya da kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'."
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() yöntemi


Delimiter Ending Character, bitiş ya da kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Açıklamalar


Örnek:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Ayrıca Bakınız

* Sınıf [IMathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)