---
title: MathBorderBoxFactory
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία ενός math border box
type: docs
url: /el/com.aspose.slides/mathborderboxfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Επιτρέπει τη δημιουργία ενός math border box

--------------------

Για συμβατότητα COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο math για εφαρμογή border box |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο border box
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο math για εφαρμογή border box |
| hideTop | boolean | Απόκρυψη Άνω Άκρης |
| hideBottom | boolean | Απόκρυψη Κάτω Άκρης |
| hideLeft | boolean | Απόκρυψη Αριστερής Άκρης |
| hideRight | boolean | Απόκρυψη Δεξιάς Άκρης |
| strikethroughHorizontal | boolean | Διέσχιση Οριζόντια Border Box |
| strikethroughVertical | boolean | Διέσχιση Κατακόρυφη Border Box |
| strikethroughBottomLeftToTopRight | boolean | Διέσχιση Border Box Κάτω-Αριστερά προς Πάνω-Δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διέσχιση Border Box Πάνω-Αριστερά προς Κάτω-Δεξιά |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο border box