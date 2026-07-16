---
title: Integral()
second_title: Référence de l'API Aspose.Slides pour C++
description: Prend l'intégrale
type: docs
weight: 196
url: /fr/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) méthode


Prend l'intégrale

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite inférieure de l'intégrale |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite supérieure de l'intégrale |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | emplacement des limites |

### Return Value

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Prend l'intégrale

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite inférieure de l'intégrale |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Limite supérieure de l'intégrale |

### Return Value

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) méthode


Prend l'intégrale sans limites

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |

### Return Value

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) méthode


Prend l'intégrale

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::String](../../../system/string/) | Limite inférieure de l'intégrale |
| upperLimit | [System::String](../../../system/string/) | Limite supérieure de l'intégrale |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | emplacement des limites |

### Return Value

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) méthode


Prend l'intégrale

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::String](../../../system/string/) | Limite inférieure de l'intégrale |
| upperLimit | [System::String](../../../system/string/) | Limite supérieure de l'intégrale |

### Return Value

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarks



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## See Also

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathNaryOperator](../../imathnaryoperator/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)