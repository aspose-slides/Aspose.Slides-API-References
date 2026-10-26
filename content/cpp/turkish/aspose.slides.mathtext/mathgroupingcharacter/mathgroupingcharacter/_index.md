---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API Referansı
description: MathGroupingCharacter sınıfının varsayılan gruplama karakteri U+23DF (ALT KAVİŞ PARANTEZ) ile yeni bir örneğini başlatır
type: docs
weight: 92
url: /tr/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) yapıcı


[MathGroupingCharacter](../) sınıfının varsayılan gruplama karakteri U+23DF (ALT KAVİŞ PARANTEZ) ile yeni bir örnek başlatır

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Çubuğun uygulandığı temel öğe |
## Açıklamalar



Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) yapıcı


Yeni bir [MathGroupingCharacter](../) sınıfının bir örneğini başlatır.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Çubuğun uygulandığı temel öğe |
| character | char16_t | Gruplama Karakteri |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Gruplama karakterinin konumu |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Grup karakterinin dikey hizalaması |
## Açıklamalar



Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)