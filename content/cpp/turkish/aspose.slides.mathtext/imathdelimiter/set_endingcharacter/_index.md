---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Ending Character sonlandırma veya kapanış sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan: ')'."
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) method

Delimiter Ending Character, sonlandırma veya kapanış sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayıcı karakterlerdir. Varsayılan: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## İlgili

* Sınıf [IMathDelimiter](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)