---
title: Integral()
second_title: Referencia de API de Aspose.Slides para C++
description: Toma la integral
type: docs
weight: 196
url: /es/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) método

Toma la integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Límite inferior de la integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Límite superior de la integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | ubicación de los límites |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Toma la integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Límite inferior de la integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Límite superior de la integral |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) método

Toma la integral sin límites

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) método

Toma la integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::String](../../../system/string/) | Límite inferior de la integral |
| upperLimit | [System::String](../../../system/string/) | Límite superior de la integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | ubicación de los límites |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) método

Toma la integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipo integral |
| lowerLimit | [System::String](../../../system/string/) | Límite inferior de la integral |
| upperLimit | [System::String](../../../system/string/) | Límite superior de la integral |

### Valor devuelto

Nueva instancia del tipo [IMathNaryOperator](../../imathnaryoperator/)
## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Ver también

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathNaryOperator](../../imathnaryoperator/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)