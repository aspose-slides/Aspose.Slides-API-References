---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Beginning Character, başlangıç ya da açılış ayırıcı karakterini belirtir. Matematiksel ayırıcılar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan değer: '('."
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metodu


Delimiter Beginning Character, başlangıç ya da açılış ayırıcı karakterini belirtir. Matematiksel ayırıcılar, parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir. Varsayılan değer: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Bakınız

* Sınıf [IMathDelimiter](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)