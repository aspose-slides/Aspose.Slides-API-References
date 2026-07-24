---
title: Enclose()
second_title: Aspose.Slides C++ API Referansı
description: Bir matematik öğesini parantez gibi belirtilen karakterler veya başka karakterler ile çerçeveleyerek kapsar
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) yöntem

Bir matematik öğesini, parantez gibi belirtilen karakterler veya başka karakterler ile çerçeveleyerek kapsar

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Dönüş Değeri

Eğer *beginningCharacter* ve *endingCharacter* null ise, ilgili özelliklere yalnızca değer atanır ve yeni bir nesne oluşturulmaz (bu örnek döndürülür). Aksi takdirde, belirtilen karakterleri çerçeve olarak içeren ve [MathDelimiter](../) örneği içinde çerçevelenmiş Delimiter türünde yeni bir matematik öğesi döndürülür.

## Açıklamalar

Örnek:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathDelimiter](../../imathdelimiter/)
* Sınıf [MathDelimiter](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)