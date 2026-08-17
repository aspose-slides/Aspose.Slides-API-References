---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Επιτρέπει τη δημιουργία ενός math border box
type: docs
url: /el/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Επιτρέπει τη δημιουργία ενός math border box

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού τύπου για να εφαρμοστεί το border box |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο border box
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Δημιουργεί ένα math border box εφαρμόζοντάς το στο στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού τύπου για να εφαρμοστεί το border box |
| hideTop | boolean | Απόκρυψη άνω άκρου |
| hideBottom | boolean | Απόκρυψη κάτω άκρου |
| hideLeft | boolean | Απόκρυψη αριστερού άκρου |
| hideRight | boolean | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | boolean | Χάραξη οριζόντιας γραμμής στο Border Box |
| strikethroughVertical | boolean | Χάραξη κάθετης γραμμής στο Border Box |
| strikethroughBottomLeftToTopRight | boolean | Χάραξη διαγώνιας γραμμής από κάτω αριστερά προς πάνω δεξιά στο Border Box |
| strikethroughTopLeftToBottomRight | boolean | Χάραξη διαγώνιας γραμμής από πάνω αριστερά προς κάτω δεξιά στο Border Box |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - νέο στοιχείο border box