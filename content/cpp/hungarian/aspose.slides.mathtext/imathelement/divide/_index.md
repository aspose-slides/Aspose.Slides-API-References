---
title: Divide()
second_title: Aspose.Slides for C++ API referencia
description: Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metódus

Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nevező |

### Visszatérési érték

új tört
## Megjegyzés



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metódus


Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nevező |

### Visszatérési érték

új tört
## Megjegyzés



Példa: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metódus


Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nevező |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tört típusa: Bar, NoBar, Skewed, Linear |

### Visszatérési érték

új tört
## Megjegyzés



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metódus


Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nevező |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tört típusa: Bar, NoBar, Skewed, Linear |

### Visszatérési érték

új tört
## Megjegyzés



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Lásd még

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFraction](../../imathfraction/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)