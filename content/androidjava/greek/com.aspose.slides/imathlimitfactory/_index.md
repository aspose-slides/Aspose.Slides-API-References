---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Επιτρέπει τη δημιουργία IMathLimit
type: docs
url: /el/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Επιτρέπει τη δημιουργία IMathLimit

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Δημιουργεί IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathLimit με όριο στο κάτω μέρος |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Δημιουργεί IMathLimit

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο ορίου |
| upperLimit | boolean | Ορίζει τη θέση του ορίου πάνω |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - νέο μαθηματικό όριο
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Δημιουργεί IMathLimit με όριο στο κάτω μέρος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό όρισμα για την εφαρμογή του ορίου |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο ορίου |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - νέο μαθηματικό όριο