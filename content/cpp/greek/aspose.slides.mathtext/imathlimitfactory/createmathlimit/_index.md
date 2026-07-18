---
title: CreateMathLimit()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Δημιουργεί IMathLimit
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) μέθοδος

Δημιουργεί [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Στοιχείο ορίου |
| upperLimit | **bool** | Ορίζει τη θέση του ορίου στην κορυφή |

### Τιμή Επιστροφής

νέο μαθηματικό όριο

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος

Δημιουργεί [IMathLimit](../../imathlimit/) με όριο στο κάτω μέρος

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Στοιχείο ορίου |

### Τιμή Επιστροφής

νέο μαθηματικό όριο

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathLimit](../../imathlimit/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathLimitFactory](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)