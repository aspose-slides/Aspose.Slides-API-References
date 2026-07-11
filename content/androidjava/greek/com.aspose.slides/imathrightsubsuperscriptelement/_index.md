---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides for Android μέσω Java API Reference
description: Καθορίζει το αντικείμενο Sub-Superscript που αποτελείται από μια βάση και έναν δείκτη και έναν εκθέτη που τοποθετούνται δεξιά της βάσης.
type: docs
url: /el/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Καθορίζει το αντικείμενο Sub-Superscript, που αποτελείται από μια βάση και έναν δείκτη και έναν εκθέτη που τοποθετούνται δεξιά της βάσης.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Παράμετρος βάσης |
| [getSubscript()](#getSubscript--) | Παράμετρος δείκτη |
| [getSuperscript()](#getSuperscript--) | Παράμετρος εκθέτη |
| [getAlignScripts()](#getAlignScripts--) | Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Παράμετρος βάσης

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Παράμετρος δείκτη

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Παράμετρος εκθέτη

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. Όταν είναι true, ο δείκτης και ο εκθέτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Επιστρέφει:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. Όταν είναι true, ο δείκτης και ο εκθέτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |