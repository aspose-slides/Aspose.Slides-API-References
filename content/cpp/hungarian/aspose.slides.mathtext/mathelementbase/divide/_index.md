---
title: Divide()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metódus


Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nevező |

### Visszatérési érték

új tört
## Megjegyzések



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metódus


Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nevező |

### Visszatérési érték

új tört
## Megjegyzések



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metódus


Létrehoz egy törtet a megadott típussal, ezzel a számlálóval és a megadott nevezővel

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nevező |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tört típusa: Bar, NoBar, Skewed, Linear |

### Visszatérési érték

új tört
## Megjegyzések



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) metódus


Létrehoz egy törtet a megadott típussal, ezzel a számlálóval és a megadott nevezővel

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Nevező |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tört típusa: Bar, NoBar, Skewed, Linear |

### Visszatérési érték

új tört
## Megjegyzések



Példa: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Lásd még

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)