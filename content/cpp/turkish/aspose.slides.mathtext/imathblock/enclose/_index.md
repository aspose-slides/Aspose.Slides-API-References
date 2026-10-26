---
title: Enclose()
second_title: Aspose.Slides for C++ API Referansı
description: Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveler ve bir ayırıcı karakterle sınırlar
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metodu


Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveler ve bir ayırıcı karakterle sınırlar

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char16_t | Bitiş karakteri (genellikle sağ köşeli parantez) |
| separatorCharacter | char16_t | Ayırıcı karakter |

### Dönüş Değeri

Belirtilen karakterleri çerçeve ve ayırıcı olarak içeren [IMathDelimiter](../../imathdelimiter/) tipinde matematik öğesi
## Açıklamalar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)