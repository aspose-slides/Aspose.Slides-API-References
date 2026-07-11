---
title: MathAccent
second_title: Aspose.Slides για Android μέσω Java API
description: Καθορίζει τη λειτουργία προφοράς που αποτελείται από μια βάση και ένα συνδυαστικό διακριτικό σημάδι. Παράδειγμα ud835udc4eu0301
type: docs
url: /el/com.aspose.slides/mathaccent/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιούμενες διεπαφές:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Καθορίζει τη λειτουργία προφοράς, που αποτελείται από μια βάση και ένα συνδυαστικό διακριτικό σημάδι Παράδειγμα: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Δημιουργεί μια μαθηματική προφορά που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα προφοράς |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Δημιουργεί μια μαθηματική προφορά που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Το όρισμα στο οποίο εφαρμόστηκε η προφορά |
| [getCharacter()](#getCharacter--) | Χαρακτήρας προφοράς Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό περισπωμένο (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Χαρακτήρας προφοράς Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό περισπωμένο (U+0302) |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Δημιουργεί μια μαθηματική προφορά που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο με την προεπιλεγμένη τιμή χαρακτήρα προφοράς

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ένα μαθηματικό στοιχείο για την εφαρμογή προφοράς |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Δημιουργεί μια μαθηματική προφορά που εφαρμόζεται σε ένα καθορισμένο μαθηματικό στοιχείο

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | μαθηματικό στοιχείο για την εφαρμογή προφοράς |
| accentCharacter | char | χαρακτήρας προφοράς |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Το όρισμα στο οποίο εφαρμόστηκε η προφορά

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Χαρακτήρας προφοράς Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό περισπωμένο (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Επιστρέφει:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Χαρακτήρας προφοράς Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό περισπωμένο (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες χαρακτήρα ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps