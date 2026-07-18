---
title: CreateMathLimit()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί IMathLimit
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) μέθοδος

Δημιουργεί [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Στοιχείο ορίου |
| upperLimit | **bool** | Ορίζει τη θέση του ορίου από πάνω |

### Τιμή επιστροφής

νέο μαθηματικό όριο

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί [IMathLimit](../../imathlimit/) με όριο στο κάτω μέρος

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Στοιχείο ορίου |

### Τιμή επιστροφής

νέο μαθηματικό όριο

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLimit](../../imathlimit/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathLimitFactory](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)