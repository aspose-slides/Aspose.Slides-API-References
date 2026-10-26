---
title: Divide()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una fracción con este numerador y el denominador especificado
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) método

Crea una fracción con este numerador y el denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominador |

### Valor devuelto

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) método

Crea una fracción con este numerador y el denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |

### Valor devuelto

nueva fracción
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) método

Crea una fracción del tipo especificado con este numerador y el denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción: Bar, NoBar, Skewed, Linear |

### Valor devuelto

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) método

Crea una fracción del tipo especificado con este numerador y el denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción: Bar, NoBar, Skewed, Linear |

### Valor devuelto

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Ver también

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)