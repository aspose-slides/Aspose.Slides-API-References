---
title: IMathSuperscriptElement
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει το αντικείμενο εκθέτη, το οποίο αποτελείται από μια βάση και έναν μικρότερου μεγέθους εκθέτη τοποθετημένο πάνω και δεξιά
type: docs
url: /el/com.aspose.slides/imathsuperscriptelement/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

Καθορίζει το αντικείμενο εκθέτη, το οποίο αποτελείται από μια βάση και έναν μικρότερο σε μέγεθος εκθέτη τοποθετημένο πάνω και δεξιά

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
>  ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSuperscript()](#getSuperscript--) | Superscript |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Βασικό όρισμα

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**Returns:**
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

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)