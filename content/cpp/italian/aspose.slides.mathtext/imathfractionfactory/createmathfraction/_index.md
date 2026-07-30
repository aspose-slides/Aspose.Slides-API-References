---
title: CreateMathFraction()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una frazione matematica
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) method

Crea una frazione matematica

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numeratore |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominatore |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo di frazione |

### Valore restituito

Nuova frazione matematica [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Crea una frazione matematica

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numeratore |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominatore |

### Valore restituito

Nuova frazione matematica [IMathFraction](../../imathfraction/)

## Vedi anche

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFractionFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)