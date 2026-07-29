---
title: Divide()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett bråk med detta täljare och specificerad nämnare
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metod

Skapar ett bråk med detta täljare och specificerad nämnare

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nämnare |

### Returvärde

nytt bråk
## Anmärkningar



Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metod


Skapar ett bråk med detta täljare och specificerad nämnare

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nämnare |

### Returvärde

nytt bråk
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metod


Skapar ett bråk av den angivna typen med detta täljare och specificerad nämnare

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nämnare |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Bråktyp: Bar, NoBar, Skewed, Linear |

### Returvärde

nytt bråk
## Anmärkningar



Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metod


Skapar ett bråk av den angivna typen med detta täljare och specificerad nämnare

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nämnare |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Bråktyp: Bar, NoBar, Skewed, Linear |

### Returvärde

nytt bråk
## Anmärkningar



Exempel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Se även

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFraction](../../imathfraction/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)