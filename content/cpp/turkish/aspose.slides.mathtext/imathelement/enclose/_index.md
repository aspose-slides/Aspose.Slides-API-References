---
title: Enclose()
second_title: Aspose.Slides for C++ API Referansı
description: Bir matematik öğesini parantez içinde kapsar
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() yöntemi


Parantez içinde bir matematik öğesini kapsar

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/) türündeki, parantez içeren matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) yöntemi


Bu öğeyi belirtilen karakterler (parantez gibi) veya çerçeveleme amaçlı diğer karakterlerle kapsar

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char16_t | Bitiş karakteri (genellikle sağ köşeli parantez) |

### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/) türündeki, belirtilen karakterlerle çerçevelenmiş matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)