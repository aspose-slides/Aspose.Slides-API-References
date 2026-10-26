---
title: MathBorderBoxFactory
second_title: Αναφορά API του Aspose.Slides για Java
description: Επιτρέπει τη δημιουργία ενός μαθηματικού πλαισίου περιγράμματος
type: docs
url: /el/com.aspose.slides/mathborderboxfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού πλαισίου περιγράμματος

--------------------

Για συμβατότητα με COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Δημιουργήστε ένα μαθηματικό πλαίσιο περιγράμματος εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για εφαρμογή πλαισίου περιγράμματος |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο πλαισίου περιγράμματος
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Δημιουργήστε ένα μαθηματικό πλαίσιο περιγράμματος εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για εφαρμογή πλαισίου περιγράμματος |
| hideTop | boolean | Απόκρυψη άνω άκρου |
| hideBottom | boolean | Απόκρυψη κάτω άκρου |
| hideLeft | boolean | Απόκρυψη αριστερού άκρου |
| hideRight | boolean | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | boolean | Διαγράψιμο πλαισίου περιγράμματος οριζόντια |
| strikethroughVertical | boolean | Διαγράψιμο πλαισίου περιγράμματος κάθετα |
| strikethroughBottomLeftToTopRight | boolean | Διαγράψιμο πλαισίου περιγράμματος κάτω-αριστερά προς πάνω-δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διαγράψιμο πλαισίου περιγράμματος πάνω-αριστερά προς κάτω-δεξιά |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο πλαισίου περιγράμματος