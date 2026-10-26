---
title: Divide()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma fração com este numerador e denominador especificado
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) método


Cria uma fração com este numerador e denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominador |

### Valor de Retorno

nova fração
## Observações



Exemplo: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) método


Cria uma fração com este numerador e denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
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
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) método


Cria uma fração do tipo especificado com este numerador e denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Denominador |
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

## IMathElement::Divide(System::String, MathFractionTypes) método


Cria uma fração do tipo especificado com este numerador e denominador especificado

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
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

## Veja Também

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)