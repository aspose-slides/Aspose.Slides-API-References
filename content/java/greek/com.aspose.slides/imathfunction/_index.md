---
title: IMathFunction
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει μια συνάρτηση ενός ορίσματος.
type: docs
url: /el/com.aspose.slides/imathfunction/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

Καθορίζει μια συνάρτηση ενός ορίσματος.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos |
| [getBase()](#getBase--) | Όρισμα Συνάρτησης |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Όρισμα Συνάρτησης

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)