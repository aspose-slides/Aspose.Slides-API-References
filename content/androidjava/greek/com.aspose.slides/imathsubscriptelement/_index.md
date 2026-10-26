---
title: IMathSubscriptElement
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει το αντικείμενο δείκτη, το οποίο αποτελείται από μια βάση και έναν μειωμένου μεγέθους δείκτη τοποθετημένο κάτω και δεξιά.
type: docs
url: /el/com.aspose.slides/imathsubscriptelement/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

Καθορίζει το αντικείμενο δείκτη, το οποίο αποτελείται από μια βάση και έναν μειωμένου μεγέθους δείκτη που τοποθετείται κάτω και δεξιά.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Βασικό όρισμα |
| [getSubscript()](#getSubscript--) | Δείκτης |
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
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Δείκτης

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)