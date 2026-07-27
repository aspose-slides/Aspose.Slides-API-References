---
title: Divide()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una fracción con este numerador y el denominador especificado
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) método


Crea una fracción con este numerador y el denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |

### Valor de retorno

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) método


Crea una fracción con este numerador y el denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |

### Valor de retorno

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) método


Crea una fracción del tipo especificado con este numerador y el denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción: Bar, NoBar, Skewed, Linear |

### Valor de retorno

nueva fracción
## Observaciones



Ejemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) método


Crea una fracción del tipo especificado con este numerador y el denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fracción: Bar, NoBar, Skewed, Linear |

### Valor de retorno

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
* Clase [IMathFraction](../../imathfraction/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)