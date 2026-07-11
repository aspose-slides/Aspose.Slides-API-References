---
title: IMathSuperscriptElement
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Καθορίζει το αντικείμενο εκθέτη που αποτελείται από μια βάση και έναν μικρότερου μεγέθους εκθέτη που τοποθετείται επάνω και δεξιά
type: docs
url: /el/com.aspose.slides/imathsuperscriptelement/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Καθορίζει το αντικείμενο εκθέτη, το οποίο αποτελείται από μια βάση και έναν μικρότερου μεγέθους εκθέτη που τοποθετείται επάνω και δεξιά

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBase()](#getBase--) | Βασικό επιχείρημα |
| [getSuperscript()](#getSuperscript--) | Εκθέτης |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασικό επιχείρημα

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Εκθέτης

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)