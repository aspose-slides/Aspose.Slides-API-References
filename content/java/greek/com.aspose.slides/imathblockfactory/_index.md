---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /el/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού μπλοκ

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Δημιουργήστε ένα μαθηματικό μπλοκ |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Δημιουργήστε ένα μαθηματικό μπλοκ και τοποθετήστε το στοιχείο σε αυτό |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Δημιουργήστε ένα μαθηματικό μπλοκ και τοποθετήστε στοιχεία σε αυτό |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Δημιουργήστε ένα μαθηματικό μπλοκ

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - νέο μαθηματικό μπλοκ
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Δημιουργήστε ένα μαθηματικό μπλοκ και τοποθετήστε το στοιχείο σε αυτό

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Ένα μαθηματικό στοιχείο |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - νέο μαθηματικό μπλοκ
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Δημιουργήστε ένα μαθηματικό μπλοκ και τοποθετήστε στοιχεία σε αυτό

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | μαθηματικά στοιχεία |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - νέο μαθηματικό μπλοκ