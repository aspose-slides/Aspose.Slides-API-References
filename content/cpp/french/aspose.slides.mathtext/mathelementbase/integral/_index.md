---
title: Integral()
second_title: Référence de l'API Aspose.Slides pour C++
description: Prend l'intégrale
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) méthode


Prend l'intégrale

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite inférieure de l'intégrale |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite supérieure de l'intégrale |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | emplacement des limites |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Prend l'intégrale

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite inférieure de l'intégrale |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite supérieure de l'intégrale |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) méthode


Prend l'intégrale sans limites

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) méthode


Prend l'intégrale

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::String](../../../system/string/) | Limite inférieure de l'intégrale |
| upperLimit | [System::String](../../../system/string/) | Limite supérieure de l'intégrale |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | emplacement des limites |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) méthode


Prend l'intégrale

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Type d'intégrale |
| lowerLimit | [System::String](../../../system/string/) | Limite inférieure de l'intégrale |
| upperLimit | [System::String](../../../system/string/) | Limite supérieure de l'intégrale |

### Valeur de retour

Nouvelle instance du type [IMathNaryOperator](../../imathnaryoperator/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Voir aussi

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathNaryOperator](../../imathnaryoperator/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)