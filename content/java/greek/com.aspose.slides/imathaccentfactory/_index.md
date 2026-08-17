---
title: IMathAccentFactory
second_title: Aspose.Slides για Java API Reference
description: Επιτρέπει τη δημιουργία ενός μαθηματικού τόνου
type: docs
url: /el/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού τόνου

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή του χαρακτήρα τόνου |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή του χαρακτήρα τόνου

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | μαθηματικό στοιχείο στο οποίο εφαρμόζεται ο τόνος |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέος μαθηματικός τόνος
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα συγκεκριμένο μαθηματικό στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | μαθηματικό στοιχείο στο οποίο εφαρμόζεται ο τόνος |
| accentCharacter | char | χαρακτήρας τόνου |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέος μαθηματικός τόνος