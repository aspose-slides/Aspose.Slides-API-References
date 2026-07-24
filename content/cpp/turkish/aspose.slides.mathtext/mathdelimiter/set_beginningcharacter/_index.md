---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Beginning Character, başlangıç veya açılış ayırıcı karakterini belirtir. Matematiksel ayırıcılar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('."
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) yöntemi


Delimiter Beginning Character, başlangıç veya açılış ayırıcı karakterini belirtir. Matematiksel ayırıcılar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ayrıca Bakınız

* Sınıf [MathDelimiter](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)