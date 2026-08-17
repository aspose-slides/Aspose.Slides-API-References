---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides για Java API Αναφορά
description: Καθορίζει το αντικείμενο Sub-Superscript, το οποίο αποτελείται από μια βάση και έναν υποδείκτη και έναν υπερδείκτη που τοποθετούνται στα δεξιά της βάσης.
type: docs
url: /el/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**All Implemented Interfaces:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Καθορίζει το αντικείμενο Sub-Superscript, το οποίο αποτελείται από μια βάση και ένα υπο-και υπερ-δείκτη τοποθετημένα στα δεξιά της βάσης.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## Κατασκευαστές

| Constructor | Description |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathRightSubSuperscriptElement. |
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Όρισμα υποδείκτη |
| [getSuperscript()](#getSuperscript--) | Όρισμα υπερδείκτη |
| [getAlignScripts()](#getAlignScripts--) | Καθορίζει την ευθυγράμμιση του υπο-και υπερ-δείκτη. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Καθορίζει την ευθυγράμμιση του υπο-και υπερ-δείκτη. |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathRightSubSuperscriptElement.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Όρισμα υποδείκτη

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
public final IMathElement getSuperscript()
```


Όρισμα υπερδείκτη

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
public final boolean getAlignScripts()
```


Καθορίζει την ευθυγράμμιση του υπο-και υπερ-δείκτη. Όταν είναι true, το subscript και το superscript ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

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
public final void setAlignScripts(boolean value)
```


Καθορίζει την ευθυγράμμιση του υπο-και υπερ-δείκτη. Όταν είναι true, το subscript και το superscript ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]