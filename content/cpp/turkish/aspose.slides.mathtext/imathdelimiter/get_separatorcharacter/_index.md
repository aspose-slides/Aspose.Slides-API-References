---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter Separator Character, ayırıcı nesnesindeki argümanları ayıran karakteri belirtir. Varsayılan: '|'."
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metod

Delimiter Separator Character, ayırıcı nesnesindeki argümanları ayıran karakteri belirtir. Varsayılan: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Açıklamalar

Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## İlgili

* Sınıf [IMathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)