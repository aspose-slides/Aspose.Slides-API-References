---
title: IMathAccent
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει τη λειτουργία του τονισμού που αποτελείται από μια βάση και ένα συνδυαστικό διακριτικό σημείο Παράδειγμα ud835udc4eu0301
type: docs
url: /el/com.aspose.slides/imathaccent/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Καθορίζει τη λειτουργία του τονισμού, που αποτελείται από μια βάση και ένα συνδυαστικό διακριτικό σημάδι Παράδειγμα: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Το επιχείρημα στο οποίο εφαρμόστηκε ο τονισμός |
| [getCharacter()](#getCharacter--) | Χαρακτήρας Τονισμού Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό Σημείο Καμπής (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Χαρακτήρας Τονισμού Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό Σημείο Καμπής (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Το επιχείρημα στο οποίο εφαρμόστηκε ο τονισμός

--------------------

> ```
> Example:
>  
>  IMMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Χαρακτήρας Τονισμού Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό Σημείο Καμπής (U+0302)

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
public abstract void setCharacter(char value)
```


Χαρακτήρας Τονισμού Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό Σημείο Καμπής (U+0302)

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