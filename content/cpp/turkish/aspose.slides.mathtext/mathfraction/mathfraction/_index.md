---
title: MathFraction()
second_title: Aspose.Slides for C++ API Referansı
description: MathFraction'ı belirtilen pay, payda ve tür ile başlatır
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) constructor


[MathFraction](../)'yi belirtilen pay, payda ve tür ile başlatır

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Pay |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Payda |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Kesir türü |
## Açıklamalar



Örnek: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


[MathFraction](../)'yi 'Bar' türünde, belirtilen pay ve payda ile başlatır

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Pay |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Payda |
## Açıklamalar



Örnek: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## Ayrıca Bakınız

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)