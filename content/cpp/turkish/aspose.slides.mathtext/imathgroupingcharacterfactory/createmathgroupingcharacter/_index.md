---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: Matematik grup karakteri oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metodu

Bir matematik grup karakteri oluşturur

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | grup karakteri uygulanacak matematik öğesi |
| character | char16_t | grup karakteri |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | grup karakterinin konumu |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | dikey hizalama |

### Dönüş Değeri

yeni grup karakteri öğesi

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metodu

Bir matematik grup karakteri oluşturur

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | grup karakteri uygulanacak matematik öğesi |

### Dönüş Değeri

yeni grup karakteri öğesi

## Ayrıca Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathGroupingCharacterFactory](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)