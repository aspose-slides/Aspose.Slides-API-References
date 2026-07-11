---
title: MathLimitFactory
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Επιτρέπει τη δημιουργία IMathLimit
type: docs
url: /el/com.aspose.slides/mathlimitfactory/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Επιτρέπει τη δημιουργία IMathLimit

--------------------

Για συμβατότητα COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Δημιουργεί IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathLimit με όριο στο κάτω μέρος |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Δημιουργεί IMathLimit

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Βασική παράμετρος για την εφαρμογή του ορίου |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο ορίου |
| upperLimit | boolean | Ορίζει τη θέση του ορίου στο πάνω μέρος |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - νέο μαθηματικό όριο
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Δημιουργεί IMathLimit με όριο στο κάτω μέρος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Βασική παράμετρος για την εφαρμογή του ορίου |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο ορίου |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - νέο μαθηματικό όριο