---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'."
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metodu

Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Ayrıca Bakınız

* Sınıf [IMathDelimiter](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)