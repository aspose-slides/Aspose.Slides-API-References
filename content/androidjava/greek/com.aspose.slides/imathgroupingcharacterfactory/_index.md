---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία ενός χαρακτήρα ομαδοποίησης μαθηματικών
type: docs
url: /el/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Επιτρέπει τη δημιουργία ενός χαρακτήρα ομαδοποίησης μαθηματικών

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Δημιουργεί έναν χαρακτήρα ομαδοποίησης μαθηματικών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για την εφαρμογή του χαρακτήρα ομαδοποίησης |
| character | char | χαρακτήρας ομαδοποίησης |
| position | int | θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | int | κάθετη στοίχιση |

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - νέο στοιχείο χαρακτήρα ομαδοποίησης
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Δημιουργεί έναν χαρακτήρα ομαδοποίησης μαθηματικών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | στοιχείο μαθηματικού για την εφαρμογή του χαρακτήρα ομαδοποίησης |

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - νέο στοιχείο χαρακτήρα ομαδοποίησης