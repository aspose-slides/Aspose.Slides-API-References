---
title: MathFraction()
second_title: Aspose.Slides för C++ API-referens
description: Initierar MathFraction med den specificerade täljaren, nämnaren och typen
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) konstruktör


Initierar [MathFraction](../) med den specificerade täljaren, nämnaren och typen

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Täljare |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nämnare |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraktionstyp |
## Anmärkningar



Exempel: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktör


Initierar en [MathFraction](../) av typen 'Bar' med den specificerade täljaren och nämnaren

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Täljare |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nämnare |
## Anmärkningar



Exempel: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## Se även

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathFraction](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)