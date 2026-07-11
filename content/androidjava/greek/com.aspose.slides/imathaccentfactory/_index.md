---
title: IMathAccentFactory
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Επιτρέπει τη δημιουργία ενός μαθηματικού τονισμού
type: docs
url: /el/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού τονισμού

--------------------

Για συμβατότητα COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Δημιουργεί ένα μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα τονισμού |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Δημιουργεί ένα μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Δημιουργεί ένα μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα τονισμού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού στο οποίο θα εφαρμοστεί ο τονισμός |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέο μαθηματικό τονισμό
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMMathElement element, char accentCharacter)
```

Δημιουργεί ένα μαθηματικό τονισμό που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού στο οποίο θα εφαρμοστεί ο τονισμός |
| accentCharacter | char | χαρακτήρας τονισμού |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέο μαθηματικό τονισμό