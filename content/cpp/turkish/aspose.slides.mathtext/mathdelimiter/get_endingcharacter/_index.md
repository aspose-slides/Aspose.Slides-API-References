---
title: get_EndingCharacter()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter Ending Character sonlandırma veya kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayan karakterlerdir. Varsayılan: ')'."
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metod


Delimiter Ending Character, sonlandırma veya kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantezler, köşeli parantezler ve süslü parantezler gibi kapsayan karakterlerdir. Varsayılan: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Diğer

* Sınıf [MathDelimiter](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)