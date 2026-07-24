---
title: CreateMathLimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt IMathLimit
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) Methode

Erstellt [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument, um die Begrenzung anzuwenden |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit-Element |
| upperLimit | **bool** | Legt die Platzierung des Limits oben fest |

### Rückgabewert

Neues mathematisches Limit

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode

Erstellt [IMathLimit](../../imathlimit/) mit Limit am unteren Ende

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument, um die Begrenzung anzuwenden |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit-Element |

### Rückgabewert

Neues mathematisches Limit

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathLimitFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)