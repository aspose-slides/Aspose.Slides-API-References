---
title: CreateMathFraction()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una fracción matemática
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) método

Crea una fracción matemática

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción |

### Valor devuelto

Nueva fracción matemática [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Crea una fracción matemática

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerador |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |

### Valor devuelto

Nueva fracción matemática [IMathFraction](../../imathfraction/)

## Ver también

* Enumeración [MathFractionTypes](../../mathfractiontypes/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IMathFraction](../../imathfraction/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathFractionFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)