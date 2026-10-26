---
title: set_BeginningCharacter()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter Beginning Character başlangıç veya açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan değer: '('."
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) yöntemi


Delimiter Beginning Character başlangıç veya açma sınırlayıcı karakterini belirtir. Matematiksel sınırlayıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayan karakterlerdir. Varsayılan değer: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ayrıca Bakınız

* Sınıf [IMathDelimiter](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)