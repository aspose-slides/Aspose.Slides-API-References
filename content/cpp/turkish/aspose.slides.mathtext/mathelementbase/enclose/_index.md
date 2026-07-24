---
title: Enclose()
second_title: C++ için Aspose.Slides API Referansı
description: Bir matematik öğesini parantez içinde kapsar
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metot


Bir matematik öğesini parantez içinde kapsar

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Dönüş Değeri

Parantez içeren [IMathDelimiter](../../imathdelimiter/) türündeki matematik öğesi
## Notlar



Örnek:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metot


Parantez gibi belirtilen karakterlerde veya başka karakterlerde çerçeveleyerek bir matematik öğesini kapsar

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Başlangıç karakteri (genellikle sol parantez) |
| endingCharacter | char16_t | Bitiş karakteri (genellikle sağ parantez) |

### Dönüş Değeri

Belirtilen karakterlerle çerçevelenmiş [IMathDelimiter](../../imathdelimiter/) türündeki matematik öğesi
## Notlar



Örnek:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathDelimiter](../../imathdelimiter/)
* Sınıf [MathElementBase](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)