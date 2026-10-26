---
title: Divide()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een breuk met deze teller en opgegeven noemer
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) methode

Maakt een breuk met deze teller en de opgegeven noemer

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Noemer |

### Retourwaarde

nieuwe breuk
## Opmerkingen

Voorbeeld: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) methode

Maakt een breuk met deze teller en de opgegeven noemer

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
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
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) methode

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Noemer |
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

## MathElementBase::Divide(System::String, MathFractionTypes) methode

Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
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
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)