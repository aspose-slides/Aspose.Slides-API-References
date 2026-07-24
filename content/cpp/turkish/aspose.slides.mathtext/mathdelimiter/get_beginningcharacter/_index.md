---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Beginning Character, başlangıç veya açma ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('."
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metod

Delimiter Beginning Character, başlangıç veya açma ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ayrıca bakınız

* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)