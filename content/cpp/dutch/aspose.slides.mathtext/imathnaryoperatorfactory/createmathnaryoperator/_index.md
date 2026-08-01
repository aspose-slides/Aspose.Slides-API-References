---
title: CreateMathNaryOperator()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt IMathNaryOperator
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathnaryoperatorfactory/createmathnaryoperator/
---
## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode

Maakt [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Het operator teken |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument om operator toe te passen |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ondergrens |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bovengrens |

### Retourwaarde

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode

Maakt [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Het operator teken |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument om operator toe te passen |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ondergrens |

### Retourwaarde

new [IMathNaryOperator](../../imathnaryoperator/)

## IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) methode

Maakt [IMathNaryOperator](../../imathnaryoperator/)

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Het operator teken |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument om operator toe te passen |

### Retourwaarde

new [IMathNaryOperator](../../imathnaryoperator/)

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathNaryOperator](../../imathnaryoperator/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathNaryOperatorFactory](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)