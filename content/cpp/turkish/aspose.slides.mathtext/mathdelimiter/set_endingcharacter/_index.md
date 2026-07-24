---
title: set_EndingCharacter()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter Ending Character, sonlandırma veya kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'."
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) yöntemi

Delimiter Ending Character, sonlandırma veya kapanış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```
## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```
## Ayrıca Bakınız

* Sınıf [MathDelimiter](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)