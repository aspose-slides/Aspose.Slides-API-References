---
title: CreateMathNaryOperator()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée IMathNaryOperator
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathnaryoperatorfactory/createmathnaryoperator/
---
## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Crée [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | Le signe de l'opérateur |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument de base sur lequel appliquer l'opérateur |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite inférieure |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite supérieure |

### Valeur de retour

new [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Crée [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | Le signe de l'opérateur |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument de base sur lequel appliquer l'opérateur |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limite inférieure |

### Valeur de retour

new [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) method


Crée [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char16_t | Le signe de l'opérateur |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument de base sur lequel appliquer l'opérateur |

### Valeur de retour

new [IMathNaryOperator](../../imathnaryoperator/)

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperatorFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)