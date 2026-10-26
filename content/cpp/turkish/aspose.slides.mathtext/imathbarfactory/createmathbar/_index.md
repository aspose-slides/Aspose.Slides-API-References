---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API Referansı
description: Eleman üzerine bir matematik çubuğu uygulayarak bir matematik çubuğu oluşturun
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) metodu

Eleman üzerine bir matematik çubuğu uygulayarak bir matematik çubuğu oluşturun

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | çubuğu uygulamak için matematik öğesi |

### Dönüş Değeri

yeni matematik çubuğu öğesi

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) metodu

Eleman üzerine bir matematik çubuğu uygulayarak bir matematik çubuğu oluşturun

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | çubuğu uygulamak için Matematik öğesi |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | çubuğun konumu |

### Dönüş Değeri

yeni matematik çubuğu öğesi

## Ayrıca Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)