---
title: IMathDelimiterFactory
second_title: Aspose.Slides για την αναφορά API Java
description: Επιτρέπει τη δημιουργία ενός μαθηματικού διαχωριστή
type: docs
url: /el/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού διαχωριστή

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Δημιουργεί ένα μαθηματικό διαχωριστή εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικό για την εφαρμογή του διαχωριστή |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - νέο μαθηματικό διαχωριστή
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Δημιουργεί ένα μαθηματικό διαχωριστή εφαρμόζοντάς το στα στοιχεία

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | στοιχεία μαθηματικά για την εφαρμογή του διαχωριστή |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - νέο μαθηματικό διαχωριστή