---
title: MathNaryOperatorFactory
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Επιτρέπει τη δημιουργία IMathNaryOperator
type: docs
url: /el/com.aspose.slides/mathnaryoperatorfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Επιτρέπει τη δημιουργία IMathNaryOperator

--------------------

Για συμβατότητα με COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό όρισμα για την εφαρμογή του τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό όρισμα για την εφαρμογή του τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό όρισμα για την εφαρμογή του τελεστή |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator