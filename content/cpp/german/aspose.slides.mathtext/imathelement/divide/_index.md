---
title: Divide()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) Methode

Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nenner |

### Rückgabewert

neuer Bruch
## Anmerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) Methode


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nenner |

### Rückgabewert

neuer Bruch
## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) Methode


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nenner |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ des Bruchs: Bar, NoBar, Skewed, Linear |

### Rückgabewert

neuer Bruch
## Anmerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) Methode


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nenner |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ des Bruchs: Bar, NoBar, Skewed, Linear |

### Rückgabewert

neuer Bruch
## Anmerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Siehe auch

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)