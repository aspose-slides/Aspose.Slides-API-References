---
title: Divide()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metoda


Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Jmenovatel |

### Návratová hodnota

nový zlomek
## Poznámky



Příklad: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metoda


Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
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
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metoda


Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Jmenovatel |
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

## MathElementBase::Divide(System::String, MathFractionTypes) metoda


Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
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

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)