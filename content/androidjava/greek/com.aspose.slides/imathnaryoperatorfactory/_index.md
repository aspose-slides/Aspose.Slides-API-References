---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Επιτρέπει τη δημιουργία IMathNaryOperator
type: docs
url: /el/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

Επιτρέπει τη δημιουργία IMathNaryOperator

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Δημιουργεί IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα για εφαρμογή του τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κατώτερο όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Ανώτερο όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - νέο IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα για εφαρμογή του τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κατώτερο όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - νέο IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Δημιουργεί IMathNaryOperator

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| operatorSymbol | char | Το σύμβολο του τελεστή |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Βασικό επιχείρημα για εφαρμογή του τελεστή |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - νέο IMathNaryOperator