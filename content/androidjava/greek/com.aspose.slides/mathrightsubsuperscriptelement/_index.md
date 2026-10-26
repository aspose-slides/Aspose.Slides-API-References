---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Καθορίζει το αντικείμενο Sub-Superscript που αποτελείται από μια βάση και έναν δείκτη και έναν εκθέτη που τοποθετούνται δεξιά της βάσης.
type: docs
url: /el/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Καθορίζει το αντικείμενο Sub-Superscript, το οποίο αποτελείται από μια βάση και έναν δείκτη και έναν εκθέτη που τοποθετούνται δεξιά της βάσης.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
>  ```

## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathRightSubSuperscriptElement. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Παράμετρος δείκτη |
| [getSuperscript()](#getSuperscript--) | Παράμετρος εκθέτη |
| [getAlignScripts()](#getAlignScripts--) | Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Καθορίζει την ευθυγράμμιση του δείκτη/εκθέτη. |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathRightSubSuperscriptElement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
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

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
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

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
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

**Returns:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λήψη στοιχείων παιδιών

**Returns:**
com.aspose.slides.IMathElement[]