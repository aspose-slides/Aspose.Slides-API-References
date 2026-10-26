---
title: Divide()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy ułamek z tym licznikiem i określonym mianownikiem
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metoda


Tworzy ułamek z tym licznikiem i określonym mianownikiem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mianownik |

### Wartość zwracana

nowy ułamek
## Uwagi



Przykład: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metoda


Tworzy ułamek z tym licznikiem i określonym mianownikiem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Mianownik |

### Wartość zwracana

nowy ułamek
## Uwagi



Przykład: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metoda


Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mianownik |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ ułamka: Bar, NoBar, Skewed, Linear |

### Wartość zwracana

nowy ułamek
## Uwagi



Przykład: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) metoda


Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Mianownik |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ ułamka: Bar, NoBar, Skewed, Linear |

### Wartość zwracana

nowy ułamek
## Uwagi



Przykład: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Zobacz także

* Wyliczenie [MathFractionTypes](../../mathfractiontypes/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathFraction](../../imathfraction/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)