---
title: Divide()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een breuk met deze teller en opgegeven noemer
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) methode

Maakt een breuk met deze teller en de opgegeven noemer

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Noemer |

### Retourwaarde

nieuwe breuk
## Opmerkingen



Voorbeeld: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) methode

Maakt een breuk met deze teller en de opgegeven noemer

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Noemer |

### Retourwaarde

nieuwe breuk
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) methode

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Noemer |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fractietype: Bar, NoBar, Skewed, Linear |

### Retourwaarde

nieuwe breuk
## Opmerkingen



Voorbeeld: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) methode

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Noemer |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fractietype: Bar, NoBar, Skewed, Linear |

### Retourwaarde

nieuwe breuk
## Opmerkingen



Voorbeeld: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Zie ook

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFraction](../../imathfraction/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)