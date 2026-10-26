---
title: get_SeparatorCharacter()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter Separator Character, ayırıcı nesnesindeki argümanları ayıran karakteri belirtir. Varsayılan: '|'."
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metod


Delimiter Separator Character, ayırıcı nesnesindeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Ayrıca Bakınız

* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)