---
title: Divide()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una frazione con questo numeratore e il denominatore specificato
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metodo


Crea una frazione con questo numeratore e il denominatore specificato

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominatore |

### Valore di ritorno

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metodo


Crea una frazione con questo numeratore e il denominatore specificato

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominatore |

### Valore di ritorno

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metodo


Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominatore |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo di frazione: Bar, NoBar, Skewed, Linear |

### Valore di ritorno

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) metodo


Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominatore |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo di frazione: Bar, NoBar, Skewed, Linear |

### Valore di ritorno

nuova frazione
## Osservazioni



Esempio: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Vedi anche

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)