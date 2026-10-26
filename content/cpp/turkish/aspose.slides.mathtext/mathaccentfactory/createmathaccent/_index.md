---
title: CreateMathAccent()
second_title: C++ için Aspose.Slides API Referansı
description: Varsayılan aksan karakteri değeriyle belirtilen bir matematik öğesine bir matematik aksanı uygular
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metot

Belirtilen matematik öğesine varsayılan aksan karakteri değeri ile bir matematik aksanı uygular

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak matematik öğesi |

### Dönüş Değeri

yeni matematik aksanı

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metot

Belirtilen matematik öğesine bir matematik aksanı uygular

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak matematik öğesi |
| accentCharacter | char16_t | aksan karakteri |

### Dönüş Değeri

yeni matematik aksanı

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathAccent](../../imathaccent/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathAccentFactory](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)