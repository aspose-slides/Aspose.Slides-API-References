---
title: Divide()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metoda


Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Jmenovatel |

### Návratová hodnota

nový zlomek
## Poznámky



Příklad: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metoda


Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Jmenovatel |

### Návratová hodnota

nový zlomek
## Poznámky



Příklad: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metoda


Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Jmenovatel |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ zlomku: Bar, NoBar, Skewed, Linear |

### Návratová hodnota

nový zlomek
## Poznámky



Příklad: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metoda


Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Jmenovatel |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Typ zlomku: Bar, NoBar, Skewed, Linear |

### Návratová hodnota

nový zlomek
## Poznámky



Příklad: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Viz také

* Výčet [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathFraction](../../imathfraction/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)