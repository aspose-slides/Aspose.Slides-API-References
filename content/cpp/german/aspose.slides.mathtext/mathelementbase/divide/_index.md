---
title: Divide()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) Methode


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nenner |

### Rückgabewert

neuer Bruch
## Bemerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) Methode


Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nenner |

### Rückgabewert

neuer Bruch
## Bemerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) Methode


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nenner |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Bruchtyp: Bar, NoBar, Skewed, Linear |

### Rückgabewert

neuer Bruch
## Bemerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) Methode


Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nenner |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Bruchtyp: Bar, NoBar, Skewed, Linear |

### Rückgabewert

neuer Bruch
## Bemerkungen



Beispiel: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Siehe auch

* Aufzählung [MathFractionTypes](../../mathfractiontypes/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFraction](../../imathfraction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)