---
title: Divide()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma fração com este numerador e denominador especificado
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) método


Cria uma fração com este numerador e denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |

### Valor de Retorno

nova fração
## Observações



Exemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) método


Cria uma fração com este numerador e denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |

### Valor de Retorno

nova fração
## Observações



Exemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) método


Cria uma fração do tipo especificado com este numerador e denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fração: Bar, NoBar, Skewed, Linear |

### Valor de Retorno

nova fração
## Observações



Exemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) método


Cria uma fração do tipo especificado com este numerador e denominador especificado

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Denominador |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Tipo de fração: Bar, NoBar, Skewed, Linear |

### Valor de Retorno

nova fração
## Observações



Exemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Ver Também

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)