---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία ενός μαθηματικού πλαισίου περιγράμματος
type: docs
url: /el/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού πλαισίου περιγράμματος

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Δημιουργεί ένα μαθηματικό πλαίσιο περιγράμματος εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για την εφαρμογή πλαισίου περιγράμματος |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο πλαισίου περιγράμματος
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Δημιουργεί ένα μαθηματικό πλαίσιο περιγράμματος εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για την εφαρμογή πλαισίου περιγράμματος |
| hideTop | boolean | Απόκρυψη Άνω Άκρου |
| hideBottom | boolean | Απόκρυψη Κάτω Άκρου |
| hideLeft | boolean | Απόκρυψη Αριστερού Άκρου |
| hideRight | boolean | Απόκρυψη Δεξιού Άκρου |
| strikethroughHorizontal | boolean | Οριζόντια Διαγραφή Πλαισίου Περιγράμματος |
| strikethroughVertical | boolean | Κατακόρυφη Διαγραφή Πλαισίου Περιγράμματος |
| strikethroughBottomLeftToTopRight | boolean | Διαγραφή Πλαισίου Περιγράμματος από Κάτω-Αριστερά προς Πάνω-Δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διαγραφή Πλαισίου Περιγράμματος από Πάνω-Αριστερά προς Κάτω-Δεξιά |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο πλαισίου περιγράμματος