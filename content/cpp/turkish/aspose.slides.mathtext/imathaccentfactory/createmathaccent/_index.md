---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle uygulanan bir matematik aksanı oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metot

Belirtilen bir matematik öğesine varsayılan aksan karakteri değeriyle uygulanan bir matematik aksanı oluşturur

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak matematik öğesi |

### Dönüş Değeri

yeni matematik aksanı

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metot

Belirtilen bir matematik öğesine uygulanan bir matematik aksanı oluşturur

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | aksan uygulanacak matematik öğesi |
| accentCharacter | char16_t | aksan karakteri |

### Dönüş Değeri

yeni matematik aksanı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathAccent](../../imathaccent/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathAccentFactory](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)