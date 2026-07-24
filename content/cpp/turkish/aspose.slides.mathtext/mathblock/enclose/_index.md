---
title: Enclose()
second_title: Aspose.Slides için C++ API Referansı
description: Bu bloğun alt elemanlarını, parantez gibi belirtilen karakterler veya başka karakterler ile çerçeveleyerek kapsar
type: docs
weight: 222
url: /tr/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metodu


Bu bloktaki alt elemanları, parantez gibi belirtilen karakterler veya başka karakterler ile çerçeveleyerek kapsar

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char16_t | Bitiş karakteri (genellikle sağ köşeli parantez) |

### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/) tipindeki matematik öğesi, belirtilen karakterleri çerçeve olarak içerir
## Açıklamalar



Örnek: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metodu


Bu bloktaki alt elemanları, parantez gibi belirtilen karakterler veya başka karakterler ile çerçeveleyerek ve bir ayırıcı karakterle sınırlayarak kapsar

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Başlangıç karakteri (genellikle sol köşeli parantez) |
| endingCharacter | char16_t | Bitiş karakteri (genellikle sağ köşeli parantez) |
| separatorCharacter | char16_t | Ayırıcı karakter |

### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/) tipindeki matematik öğesi, belirtilen karakterleri çerçeve ve ayraç olarak içerir
## Açıklamalar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)