---
title: Integral()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o integral
type: docs
weight: 196
url: /pt/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) method

Obtém o integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite inferior do integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite superior do integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | localização dos limites |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Obtém o integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite inferior do integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite superior do integral |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) method

Obtém o integral sem limites

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) method

Obtém o integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::String](../../../system/string/) | Limite inferior do integral |
| upperLimit | [System::String](../../../system/string/) | Limite superior do integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | localização dos limites |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) method

Obtém o integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::String](../../../system/string/) | Limite inferior do integral |
| upperLimit | [System::String](../../../system/string/) | Limite superior do integral |

### Valor de Retorno

Nova instância do tipo [IMathNaryOperator](../../imathnaryoperator/)

## Observações



Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Veja Também

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)