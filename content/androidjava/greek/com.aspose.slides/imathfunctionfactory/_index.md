---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Επιτρέπει τη δημιουργία μιας μαθηματικής συνάρτησης
type: docs
url: /el/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Επιτρέπει τη δημιουργία μιας μαθηματικής συνάρτησης

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί μαθηματική συνάρτηση |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Δημιουργεί μαθηματική συνάρτηση |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Δημιουργεί μαθηματική συνάρτηση

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο που χρησιμοποιείται ως όνομα συνάρτησης |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο που χρησιμοποιείται ως όρισμα συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - νέα μαθηματική συνάρτηση
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Δημιουργεί μαθηματική συνάρτηση

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String | Όνομα συνάρτησης |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Στοιχείο που χρησιμοποιείται ως όρισμα συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - νέα μαθηματική συνάρτηση