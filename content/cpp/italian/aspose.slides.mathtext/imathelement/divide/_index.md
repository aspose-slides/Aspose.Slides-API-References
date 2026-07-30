---
title: Divide()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una frazione con questo numeratore e il denominatore specificato
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metodo


Crea una frazione con questo numeratore e il denominatore specificato

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominatore |

### Valore restituito

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metodo


Crea una frazione con questo numeratore e il denominatore specificato

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominatore |

### Valore restituito

nuova frazione
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metodo


Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominatore |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo di frazione: Bar, NoBar, Skewed, Linear |

### Valore restituito

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metodo


Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominatore |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo di frazione: Bar, NoBar, Skewed, Linear |

### Valore restituito

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Vedi anche

* Enumerazione [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)