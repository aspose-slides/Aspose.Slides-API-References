---
title: set_SeparatorCharacter()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'."
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metod


Delimiter Separator Character, ayraç nesnesindeki bağımsız değişkenleri ayıran karakteri belirtir. Varsayılan: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Bakınız

* Sınıf [MathDelimiter](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)