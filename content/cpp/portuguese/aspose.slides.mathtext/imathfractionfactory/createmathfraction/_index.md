---
title: CreateMathFraction()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma fração matemática
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) método

Cria uma fração matemática

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fração |

### Valor de Retorno

Nova fração matemática [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Cria uma fração matemática

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |

### Valor de Retorno

Nova fração matemática [IMathFraction](../../imathfraction/)

## Ver Também

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathFraction](../../imathfraction/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFractionFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)