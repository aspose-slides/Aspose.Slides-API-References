---
title: MathAccentFactory
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Επιτρέπει τη δημιουργία ενός μαθηματικού τόνου
type: docs
url: /el/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού τόνου

--------------------

Για συμβατότητα με COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα τόνου

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | μαθηματικό στοιχείο για την εφαρμογή του τόνου |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέο μαθηματικό τόνο
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Δημιουργεί ένα μαθηματικό τόνο που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | μαθηματικό στοιχείο για την εφαρμογή του τόνου |
| accentCharacter | char | χαρακτήρας τόνου |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - νέο μαθηματικό τόνο