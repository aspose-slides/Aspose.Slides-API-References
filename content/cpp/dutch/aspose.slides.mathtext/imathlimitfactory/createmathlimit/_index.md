---
title: CreateMathLimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert IMathLimit
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) methode


Maakt [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument om de limiet toe te passen |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limitelement |
| upperLimit | **bool** | Stelt de plaatsing van de limiet bovenaan in |

### Retourwaarde

nieuwe wiskundige limiet

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode


Maakt [IMathLimit](../../imathlimit/) met limiet onderaan

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument om de limiet toe te passen |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limitelement |

### Retourwaarde

nieuwe wiskundige limiet

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathLimitFactory](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)