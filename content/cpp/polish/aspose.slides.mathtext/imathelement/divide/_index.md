---
title: Divide()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy ułamek z tym licznikiem i określonym mianownikiem
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metoda


Tworzy ułamek z tym licznikiem i określonym mianownikiem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Mianownik |

### Wartość zwracana

nowy ułamek
## Uwagi



Przykład: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metoda


Tworzy ułamek z tym licznikiem i określonym mianownikiem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
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
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metoda


Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Mianownik |
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

## IMathElement::Divide(System::String, MathFractionTypes) metoda


Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
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
* DefinicjaTypu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathFraction](../../imathfraction/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)