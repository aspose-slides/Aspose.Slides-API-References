---
title: IMathAccent
second_title: Aspose.Slides για την αναφορά API Java
description: Καθορίζει τη λειτουργία τονισμού που αποτελείται από μια βάση και ένα συνδυαζόμενο διακριτικό σημάδι. Παράδειγμα ud835udc4eu0301
type: docs
url: /el/com.aspose.slides/imathaccent/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Καθορίζει τη λειτουργία τονισμού, αποτελούμενη από μια βάση και ένα συνδυαζόμενο διακριτικό σημείο Παράδειγμα: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Το όρισμα στο οποίο εφαρμόστηκε ο τονισμός |
| [getCharacter()](#getCharacter--) | Χαρακτήρας τονισμού Η τιμή πρέπει να βρίσκεται στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαζόμενος Τονισμός Καμπύλης (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Χαρακτήρας τονισμού Η τιμή πρέπει να βρίσκεται στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαζόμενος Τονισμός Καμπύλης (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Το όρισμα στο οποίο εφαρμόστηκε ο τονισμός

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
public abstract char getCharacter()
```


Χαρακτήρας τονισμού Η τιμή πρέπει να βρίσκεται στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαζόμενος Τονισμός Καμπύλης (U+0302)

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


Χαρακτήρας τονισμού Η τιμή πρέπει να βρίσκεται στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαζόμενος Τονισμός Καμπύλης (U+0302)

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