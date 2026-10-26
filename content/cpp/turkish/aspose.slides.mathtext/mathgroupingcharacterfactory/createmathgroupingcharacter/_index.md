---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: Bir matematik gruplama karakteri oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metod

Bir matematik gruplama karakteri oluşturur

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | gruplama karakteri uygulanacak matematik öğesi |
| character | char16_t | gruplama karakteri |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | gruplama karakterinin konumu |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | dikey hizalama |

### Dönüş Değeri

yeni gruplama karakteri öğesi

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metod

Bir matematik gruplama karakteri oluşturur

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | gruplama karakteri uygulanacak matematik öğesi |

### Dönüş Değeri

yeni gruplama karakteri öğesi

## Ayrıca Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)